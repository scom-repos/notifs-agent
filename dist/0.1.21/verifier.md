::: var
primary: #2563eb
accent: var(--color-accent-main)
secondary: var(--color-text-secondary)
divider: var(--color-border)
warning: var(--color-warning-main)
buttonVariants:
  foreground:
    backgroundColor: "#fff"
    color: "#2563eb"
    border: "1px solid #2563eb"
    borderRadius: "8px"
    padding: "0.75rem 2rem"
    fontSize: "1.125rem"
    fontWeight: 600
  outline:
    backgroundColor: "transparent"
    color: "#2563eb"
    border: "2px solid #2563eb"
    borderRadius: "8px"
    padding: "0.375rem 0.75rem"
    fontSize: "0.875rem"
    fontWeight: 600
  primary:
    backgroundColor: "#2563eb"
    color: "#fff"
    border: "1px solid #2563eb"
    borderRadius: "8px"
    padding: "0.75rem 2rem"
    fontSize: "1.125rem"
    fontWeight: 600
  danger:
    backgroundColor: "#ef4444"
    color: "#fff"
    border: "none"
    borderRadius: "8px"
    padding: "0.75rem 2rem"
    fontSize: "1.125rem"
    fontWeight: 600
  accent:
    backgroundColor: "#0d968b"
    color: "#fff"
    border: "2px solid #0d968b"
    borderRadius: "8px"
    padding: "0.75rem 2rem"
    fontSize: "1.125rem"
    fontWeight: 600
:::

::: page-section {"className": "theme-gradient-dark-to-primary theme-spacing-section"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-gap)", "alignItems": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-2 theme-text-white"}
    # TrustRoot ::gradient[Verifier]{className: theme-gradient-primary-to-accent-text}
    :::
    ::: page-text {"className": "theme-text-xl theme-text-light-gray theme-margin-bottom-3", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Enter a domain or agent below to check if it's officially verified by TrustRoot.
    :::
  :::
:::

::: page-section {"className": "theme-gradient-dark-to-primary theme-spacing-lg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-gap)", "alignItems": "center"}
    ::: page-verifier-input {"background": {"color": "#fff"}, "font": {"color": "#020817"}}
    :::
  :::
:::

::: page-section {"className": "theme-spacing-lg theme-secondary-bg"}
  ::: page-block {"className": "theme-container-6xl", "align": "center", "width": "100%"}
    ::: page-text {"textAlign": "center", "className": "theme-text-2xl-bold theme-margin-bottom-2"}
    ## History
    :::
    ::: page-tabs {"justifyContent": "start", "width": "100%", "border": {"bottom": {"color": "{divider}", "width": "1px", "style": "solid"}}, "tab": {"active": {"font": {"color": "{primary}"}, "border": {"bottom": {"color": "{primary}", "width": "1px", "style": "solid"}}}}}
      ::: tab {"padding": {"top": "0.5rem", "bottom": "0.5rem", "left": "1rem", "right": "1rem"}, "background": {"color": "transparent"}}
        title: Domain
        tabKey: domain
        icon: Globe
        ::: page-table {}
          ::: search-key
            key: domain
          :::
          ::: column
            key: domain
            header: Domain
          :::
          ::: column
            key: status
            header: Status
            align: center
            ::: page-block {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
              ::: page-block {"stack": {"shrink": "0"}}
                ::: page-icon {"name": "{row.status === 'verified' ? 'ShieldCheck' : row.status === 'failed' ? 'ShieldX' : 'ShieldQuestion'}", "color": "{row.status === 'verified' ? '{accent}' : row.status === 'failed' ? '{warning}' : '{secondary}'}", "size": "1rem" }
                :::
              :::
              ::: page-text {"className": "theme-text-capitalize", "font": {"color": "{row.status === 'verified' ? '{accent}' : row.status === 'failed' ? '{warning}' : '{secondary}'}", "weight": 600, "size": "var(--font-size-sm)"}}
              {row.status}
              :::
            :::
          :::
          ::: column
            key: trootHash
            header: Asset Hash
            wrap: true
            minWidth: 20rem
          :::
          ::: column
            key: trootGuardHash
            header: Trust Root Guard Hash
            wrap: true
            minWidth: 20rem
          :::
          ::: column
            key: action
            align: right
            header:
            ::: page-link {"url": "/verifier/history/domain/{row.id}", "textDecoration": "none"}
              ::: page-block {"stack": {"shrink": "0"}}
                ::: page-icon {"name": "View", "size": "1rem", "color": "{primary}"}
                :::
              :::
              ::: page-text {"lineHeight": 1, "font": {"color": "{primary}"}}
              View
              :::
            :::
          :::

          ::: filter
            id: all
            label: All
          :::
          ::: filter
            id: verified
            label: Verified
            icon: ShieldCheck
          :::
          ::: filter
            id: failed
            label: Failed
            icon: ShieldX
          :::
          ::: filter
            id: unverified
            label: Unverified
            icon: ShieldQuestion
          :::
          ::: fetch-data
          endpoint: https://trustroot.org/api/verifier/v0/history/domain
          method: GET
          params:
            page: 1
            pageSize: 10
          headers:
            Authorization: "Bearer {env.API_TOKEN}"
          as: "domains"
          :::
        :::
      :::
      ::: tab {"padding": {"top": "0.5rem", "bottom": "0.5rem", "left": "1rem", "right": "1rem"}, "background": {"color": "transparent"}}
        title: Agent
        tabKey: agent
        icon: Bot
        ::: page-table {}
          ::: search-key
            key: agent
          :::
          ::: column
            key: name
            header: Agent
          :::
          ::: column
            key: status
            header: Status
            align: center
            ::: page-block {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
              ::: page-block {"stack": {"shrink": "0"}}
                ::: page-icon {"name": "{row.status === 'verified' ? 'ShieldCheck' : row.status === 'failed' ? 'ShieldX' : 'ShieldQuestion'}", "color": "{row.status === 'verified' ? '{accent}' : row.status === 'failed' ? '{warning}' : '{secondary}'}", "size": "1rem" }
                :::
              :::
              ::: page-text {"className": "theme-text-capitalize", "font": {"color": "{row.status === 'verified' ? '{accent}' : row.status === 'failed' ? '{warning}' : '{secondary}'}", "weight": 600, "size": "var(--font-size-sm)"}}
              {row.status}
              :::
            :::
          :::
          ::: column
            key: version
            header: Version
            wrap: true
          :::
          ::: column
            key: npub
            header: Public Key
            wrap: true
          :::
          ::: column
            key: action
            align: right
            header:
            ::: page-link {"url": "/verifier/history/agent/{row.id}", "textDecoration": "none"}
              ::: page-block {"stack": {"shrink": "0"}}
                ::: page-icon {"name": "View", "size": "1rem", "color": "{primary}"}
                :::
              :::
              ::: page-text {"lineHeight": 1, "font": {"color": "{primary}"}}
              View
              :::
            :::
          :::

          ::: filter
            id: all
            label: All
          :::
          ::: filter
            id: verified
            label: Verified
            icon: ShieldCheck
          :::
          ::: filter
            id: failed
            label: Failed
            icon: ShieldX
          :::
          ::: fetch-data
          endpoint: "https://trustroot.org/api/verifier/v0/history/agent"
          method: "GET"
          params:
            page: 1
            pageSize: 10
          headers:
            Authorization: "Bearer {env.API_TOKEN}"
          as: "domains"
          :::
        :::
      :::
    :::
  :::
:::
