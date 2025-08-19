::: var
primary: var(--color-primary-main)
accent: var(--color-accent-main)
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
    color: "#fff"
    border: "2px solid #fff"
    borderRadius: "8px"
    padding: "0.75rem 2rem"
    fontSize: "1.125rem"
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
iconVariants:
  primary:
    backgroundColor: "#2466eb33"
    color: "#2563eb"
  accent:
    backgroundColor: "#0d968b33"
    color: "#0d968b"
  error:
    backgroundColor: "#ef444433"
    color: "#ef4444"
  warning:
    backgroundColor: "#f9731633"
    color: "#f97316"
  purple:
    backgroundColor: "#8b5cf633"
    color: "#8b5cf6"
  green:
    backgroundColor: "#16a24933"
    color: "#16a249"
:::

::: page-section {"className": "theme-spacing-section theme-card-subtle-bg"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "alignItems": "center", "gap": "1.5rem"}
    ::: page-text {"textAlign": "center"}
    # Let's Build the Future of ::gradient[Digital Trust Together]{color: {primary}}
    :::
    ::: page-text {"textAlign":"center", "className": "theme-container-3xl theme-text-muted theme-text-2xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
    Whether you're interested in partnerships, technical integration, or learning more about TrustRoot, our team is here to help you build secure, verifiable digital experiences.
    :::
  :::
:::

::: page-section {"className":"theme-secondary-bg"}
  ::: page-block {"className": "theme-margin-bottom-4 theme-container-4xl", "gap": "1rem", "align": "center"}
    ::: page-text {"textAlign": "center"}
    ## How Can We Help?
    :::
    ::: page-text {"className": "theme-text-xl-secondary","textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Choose the contact method that best fits your needs, or use the general form below to reach out.
    :::
  :::

  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-feature-grid {"image":{"width":"5rem","height":"auto"},"columnsPerRow": 4,"textAlign": "center"}
      ::: feature
        icon: {"name": "Building", "variant": "primary"}
        title: Partnership Inquiries
        description: Strategic partnerships and business development
        link: { "caption": "partnerships@trustroot.com", "url": "mailto:partnerships@trustroot.com" }
      :::
      ::: feature
        icon: {"name": "Code", "variant": "primary"}
        title: Developer Support
        description: Technical questions and integration support
        link: { "caption": "developers@trustroot.com", "url": "mailto:developers@trustroot.com" }
      :::
      ::: feature
        icon: {"name": "Users", "variant": "primary"}
        title: Enterprise Sales
        description: Custom solutions for large organizations
        link: { "caption": "enterprise@trustroot.com", "url": "mailto:enterprise@trustroot.com" }
      :::
      ::: feature
        icon: {"name": "MessageCircle", "variant": "primary"}
        title: General Inquiries
        description: Questions about TrustRoot and our services
        link: { "caption": "contact@trustroot.org", "url": "mailto:contact@trustroot.org" }
      :::
    :::
  :::
:::

::: page-section {"className":"theme-background-bg"}
  ::: page-block {"className": "theme-container-lg", "align": "center", "gap": "1rem"}
    ::: page-text {"textAlign": "center"}
    ### Contact Information
    :::
    ::: page-text {"textAlign":"center", "className": "theme-margin-bottom-2 theme-text-lg-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    We're thrilled to connect during our testnet phase—let's build a safer digital world together!
    :::
  :::

  ::: page-block {"className": "theme-container-lg", "align": "center", "gap": "2rem"}
    ::: page-block {"preset": "--component-card-gradientPrimary"}
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1.5rem"}
        ::: page-icon {"name": "Mail", "size": "2rem", "color": "{primary}"}
        :::
        ::: page-block {"className": "theme-stack-flex-1", "gap": "0.5rem"}
          ::: page-text {"className": "theme-text-lg-bold"}
          Email Us
          :::
          ::: page-text {"className": "theme-text-secondary"}
          For general inquiries or partnership proposals.
          :::
          ::: page-link {"className": "theme-text-primary theme-text-bold"}
          [contact@trustroot.org](mailto:contact@trustroot.org)
          :::
        :::
      :::
    :::

    ::: page-block {"preset": "--component-card-gradientAccent"}
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1.5rem"}
        ::: page-icon {"name": "MessageSquare", "size": "2rem", "color": "{accent}"}
        :::
        ::: page-block {"className": "theme-stack-flex-1", "gap": "0.5rem"}
          ::: page-text {"className": "theme-text-lg-bold"}
          Community Chat
          :::
          ::: page-text {"className": "theme-text-secondary"}
          Follow us on X (@TrustRootOrg) and join our Telegram Group for updates.
          :::
          ::: page-stack {"direction": "horizontal", "gap": "1rem"}
            ::: page-link {"className": "theme-text-primary theme-text-bold"}
            [Telegram Group](#)
            :::
            ::: page-link {"className": "theme-text-primary theme-text-bold"}
            [X (Twitter)](https://x.com/TrustRootOrg)
            :::
          :::
        :::
      :::
    :::
  :::
:::
