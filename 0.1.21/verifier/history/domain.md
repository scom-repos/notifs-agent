::: var
primary: "#2563eb"
accent: var(--color-accent-main)
secondary: var(--color-text-secondary)
warning: var(--color-warning-main)
error: var(--color-error-main)
spacing:
  item:
    top: "2rem"
    bottom: "2rem"
    left: "2rem"
    right: "2rem"
:::

::: fetch-data
endpoint: https://trustroot.org/api/verifier/v0/history/domain/:id
method: GET
headers:
  Authorization: "Bearer {env.API_TOKEN}"
as: "record"
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-5xl theme-margin-bottom-2", "align": "center"}
    ::: page-link {"url": "/verifier?tab=domain", "textDecoration": "none"}
      ::: page-icon {"name": "ArrowLeft", "size": "1rem", "color": "{primary}"}
      :::
      ::: page-text {"font": {"color": "{primary}", "weight": 500}, "lineHeight": 1}
      Back to Verifier
      :::
    :::
  :::

  ::: page-block {"className": "theme-container-5xl theme-spacing-lg theme-border theme-background-bg theme-box-shadow-xl theme-border-radius-2xl", "align": "center", "gap": "1.5rem"}
    ::: page-text {"className": "theme-text-bolder"}
    ### Domain Verification Details
    :::

    ::: page-block {"display": "{record.error ? 'block' : 'none'}"}
      ::: page-stack {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center", "justifyContent": "center"}
        ::: page-icon { "name": "AlertCircle", "color": "{error}", "size": "1rem"}
        :::
        ::: page-text {"className": "theme-text-sm-bold theme-text-error"}
        {record.error || ''}
        :::
      :::
    :::
    
    ::: page-block {"gap": "1rem", "display": "::expression[record.error ? 'none' : 'flex']"}
      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Domain
        :::
        ::: page-link {"url": "::expression[normalizeURL(record.domain)]", "textDecoration": "none"}
          ::: page-text {"className": "theme-text-sm-bold theme-text-primary"}
          {record.domain}
          :::
          ::: page-icon {"name": "ExternalLink", "color": "{primary}", "size": "0.75rem"}
          :::
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Status
        :::
        ::: page-block {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center", "font": {"color": "{record.status === 'verified' ? '{accent}' : record.status === 'failed' ? '{warning}' : '{secondary}'}"}}
          ::: page-icon {"name": "{record.status === 'verified' ? 'ShieldCheck' : record.status === 'failed' ? 'ShieldX' : 'ShieldQuestion'}", "color": "currentColor", "size": "1rem" }
          :::
          ::: page-text {"font": {"color": "currentColor"}, "className": "theme-text-sm-bold theme-text-capitalize"}
          {record.status}
          :::
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Asset Hash
        :::
        ::: page-text {"className": "theme-text-sm-bold theme-text-secondary", "overflowWrap": "anywhere"}
        {record.trootHash || 'N/A'}
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Trust Root Guard Hash
        :::
        ::: page-text {"className": "theme-text-sm-bold theme-text-secondary", "overflowWrap": "anywhere"}
        {record.trootGuardHash || 'N/A'}
        :::
      :::

      ::: page-block {"gap": "0.25rem"}
        ::: page-text {"className": "theme-text-xl-bold"}
        Created At
        :::
        ::: page-text {"className": "theme-text-sm-bold theme-text-secondary"}
        ::expression[new Date(record.createdAt * 1000).toLocaleString()]
        :::
      :::
    :::
  :::
::: 