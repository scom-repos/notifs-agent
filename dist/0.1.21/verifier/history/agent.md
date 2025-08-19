::: var
primary: "#2563eb"
accent: var(--color-accent-main)
secondary: var(--color-text-secondary)
warning: var(--color-warning-main)
spacing:
  item:
    top: "2rem"
    bottom: "2rem"
    left: "2rem"
    right: "2rem"
buttonVariants:
  outline:
    backgroundColor: "transparent"
    color: "#2563eb"
    border: "2px solid #2563eb"
    borderRadius: "8px"
    padding: "0.375rem 0.75rem"
    fontSize: "0.875rem"
    fontWeight: 600
:::

::: fetch-data
endpoint: https://trustroot.org/api/verifier/v0/history/agent/:id
method: GET
headers:
  Authorization: "Bearer {env.API_TOKEN}"
as: "record"
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-5xl theme-margin-bottom-2", "align": "center"}
    ::: page-link {"url": "/verifier?tab=agent", "textDecoration": "none"}
      ::: page-icon {"name": "ArrowLeft", "size": "1rem", "color": "{primary}"}
      :::
      ::: page-text {"font": {"color": "{primary}", "weight": 500}, "lineHeight": 1}
      Back to Verifier
      :::
    :::
  :::

  ::: page-block {"className": "theme-container-5xl theme-spacing-lg theme-border theme-background-bg theme-box-shadow-xl theme-border-radius-2xl", "align": "center", "gap": "1.5rem"}
    ::: page-text {"className": "theme-text-bolder"}
    ### Agent Verification Details
    :::

    ::: page-block {"display": "{record.error ? 'block' : 'none'}"}
      ::: page-stack {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center", "justifyContent": "center"}
        ::: page-icon { "name": "AlertCircle", "color": "{warning}", "size": "1rem"}
        :::
        ::: page-text {"className": "theme-text-sm-bold theme-text-error"}
        {record.error || ''}
        :::
      :::
    :::
    
    ::: page-block {"gap": "1rem", "display": "::expression[record.error ? 'none' : 'flex']"}
      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Endpoint
        :::
        ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
          ::: page-block {"stack": {"shrink": "0"}}
            ::: page-icon { "name": "{record.endpoint ? 'ShieldCheck' : 'ShieldX'}", "color": "{record.endpoint ? '{accent}' : '{warning}'}", "size": "1rem" }
            :::
          :::
          ::: page-link {"url": "::expression[normalizeURL(`${record.endpoint}/${record.name}`)]", "textDecoration": "none"}
            ::: page-text {"className": "theme-text-sm-bold theme-text-primary", "overflowWrap": "anywhere"}
            ::expression[normalizeURL(`${record.endpoint}/${record.name}`)]
            :::
            ::: page-icon {"name": "ExternalLink", "color": "{primary}", "size": "0.75rem"}
            :::
          :::
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Agent
        :::
        ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
          ::: page-block {"stack": {"shrink": "0"}}
            ::: page-icon { "name": "{record.name ? 'ShieldCheck' : 'ShieldX'}", "color": "{record.name ? '{accent}' : '{warning}'}", "size": "1rem" }
            :::
          :::
          ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
          {record.name}
          :::
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Status
        :::
        ::: page-block {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
          ::: page-block {"stack": {"shrink": "0"}}
            ::: page-icon {"name": "{record.status === 'verified' ? 'ShieldCheck' : record.status === 'failed' ? 'ShieldX' : 'ShieldQuestion'}", "color": "{record.status === 'verified' ? '{accent}' : record.status === 'failed' ? '{warning}' : '{secondary}'}", "size": "1rem" }
            :::
          :::
          ::: page-text {"font": {"color": "{record.status === 'verified' ? '{accent}' : record.status === 'failed' ? '{warning}' : '{secondary}'}"}, "className": "theme-text-sm-bold theme-text-capitalize"}
          {record.status}
          :::
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Version
        :::
        ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
          ::: page-block {"stack": {"shrink": "0"}}
            ::: page-icon { "name": "{record.version ? 'ShieldCheck' : 'ShieldX'}", "color": "{record.version ? '{accent}' : '{warning}'}", "size": "1rem" }
            :::
          :::
          ::: page-link {"url": "::expression[constructDockerHubUrl(record.version)]", "textDecoration": "none"}
            ::: page-text {"className": "theme-text-sm-bold theme-text-primary", "overflowWrap": "anywhere"}
            {record.version}
            :::
            ::: page-icon {"name": "ExternalLink", "color": "{primary}", "size": "0.75rem"}
            :::
          :::
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Public Key
        :::
        ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
          ::: page-block {"stack": {"shrink": "0"}}
            ::: page-icon { "name": "{record.npub ? 'ShieldCheck' : 'ShieldX'}", "color": "{record.npub || record.platform === 'aws' ? '{accent}' : '{warning}'}", "size": "1rem" }
            :::
          :::
          ::: page-text {"className": "theme-text-sm-bold theme-text-secondary", "overflowWrap": "anywhere"}
          {record.npub || '-'}
          :::
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Running on secure enclave?
        :::
        ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
          ::: page-block {"stack": {"shrink": "0"}}
            ::: page-icon { "name": "{record.enclave ? 'ShieldCheck' : 'ShieldX'}", "color": "{record.enclave ? '{accent}' : '{warning}'}", "size": "1rem" }
            :::
          :::
          ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
          Agent is running {record.enclave ? 'on' : 'outside'} the secure enclave
          :::
        :::
      :::
      
      ::: page-block {"margin": {"top": "0.5rem"}, "padding": {"top": "0.5rem"}, "className": "theme-border-top"}
      :::

      ::: page-stack {"display": "{record.enclave ? 'flex' : 'none'}", "gap": "1rem"}
        ::: page-stack {"direction": "horizontal", "justifyContent": "space-between", "alignItems": "center", "mediaQueries": [{"maxWidth": "768px", "properties": {"direction": "vertical", "alignItems": "start", "gap": "0.5rem"}}]}
          ::: page-block {"direction": "horizontal", "alignItems": "center", "gap": "0.5rem"}
            ::: page-icon {"name": "Castle", "size": "1.5rem"}
            :::
            ::: page-text {"font": {"size": "var(--font-size-xl)", "weight": 600}}
            Secure Enclave
            :::
          :::
          ::: page-stack {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
            ::: page-button {"align": "center"}
              ::: button
                caption: Download Proof
                url: ::expression[normalizeURL(`${record.endpoint}/attest/attest?raw`)]
                icon: Download
                download: TDX-Quote_{record.name}.txt
                variant: outline
              :::
            :::
            ::: page-block {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center", "font": {"color": "{record.enclave ? '{accent}' : '{warning}'}"}}
              ::: page-icon { "name": "{record.enclave ? 'ShieldCheck' : 'ShieldX'}", "color": "currentColor", "size": "1rem" }
              :::
              ::: page-text {"className": "theme-text-capitalize", "font": {"color": "currentColor", "weight": 600, "size": "var(--font-size-sm)"}}
              {record.enclave && !record.enclave.invalidFields?.length ? "verified" : "failed"}
              :::
            :::
          :::
        :::
        
        ::: page-block {"gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          Service Provider
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('serviceProvider', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('serviceProvider', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
            {record.enclave.serviceProvider}
            :::
          :::
        :::
        
        ::: page-block {"gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          Type
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('type', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('type', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
            {record.enclave.type}
            :::
          :::
        :::
  
        ::: page-block {"display": "{record.platform == 'phala' ? 'flex' : 'none'}", "gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          CPU Security Version
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('cpu', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('cpu', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
            {record.enclave.cpu}
            :::
          :::
        :::

        ::: page-block {"display": "{record.platform == 'phala' ? 'flex' : 'none'}", "gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          Code Measurement (MR_ENCLAVE)
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('mrEnclave', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('mrEnclave', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary", "overflowWrap": "anywhere"}
            {record.enclave.mrEnclave}
            :::
          :::
        :::
  
        ::: page-block {"display": "{record.platform == 'phala' ? 'flex' : 'none'}", "gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          Signer Identity (MR_SIGNER)
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('mrSigner', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('mrSigner', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary", "overflowWrap": "anywhere"}
            {record.enclave.mrSigner}
            :::
          :::
        :::

        ::: page-block {"display": "{record.platform == 'phala' ? 'flex' : 'none'}", "gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          Certificate Status
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('mrSigner', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('mrSigner', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
            {record.enclave.certificate.status === 'valid' ? `Chain valid until ::expression[formatDate(record.enclave.certificate.until)], issued by Intel SGX Root CA` : 'Invalid or unknown issuer'}
            :::
          :::
        :::
  
        ::: page-block {"display": "{record.platform == 'aws' ? 'flex' : 'none'}", "gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          Enclave Id
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('enclaveId', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('enclaveId', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
            {record.enclave.enclaveId}
            :::
          :::
        :::
  
        ::: page-block {"display": "{record.platform == 'aws' ? 'flex' : 'none'}", "gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          Nonce
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('nonce', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('nonce', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
            {record.enclave.nonce || '-'}
            :::
          :::
        :::
  
        ::: page-block {"display": "{record.platform == 'aws' ? 'flex' : 'none'}", "gap": "0.25rem"}
          ::: page-text {"className": "theme-text-xl-bold"}
          Public Key
          :::
          ::: page-stack { "direction": "horizontal", "gap": "0.5rem", "alignItems": "center" }
            ::: page-block {"stack": {"shrink": "0"}}
              ::: page-icon { "name": "::expression[isFieldInvalid('publicKey', record.enclave) ? 'ShieldCheck' : 'ShieldX']", "color": "::expression[isFieldInvalid('publicKey', record.enclave) ? '{accent}' : '{warning}']", "size": "1rem" }
              :::
            :::
            ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
            {record.enclave.publicKey || '-'}
            :::
          :::
        :::

        ::: enclave-pcrs {"display": "{record.platform == 'aws' ? 'flex' : 'none'}"}
          pcrs: {record.enclave.pcrs}
        :::
      :::
    :::
  :::
::: 