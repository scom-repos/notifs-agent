::: var
primary: "#2563eb"
accent: "#0d968b"
purple: "#9234ea"
green: "#16a249"
error: "#ef4444"
warning: "#f97316"
primaryBg: "#2466eb33"
accentBg: "#ccfbf1"
greenBg: "#f0fdf4"
purpleBg: "#8b5cf633"
warningBg: "#f9731633"
errorBg: "#ef444433"

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

::: page-section {"className": "theme-hero-bg theme-spacing-hero"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    # TrustRoot: The Source of ::gradient[Verifiable Trust]{className: theme-gradient-primary}
    :::
    ::: page-text {"className": "theme-text-secondary theme-text-2xl", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
    Ensuring Authentic Interactions and Uncompromised Operations for AI Agents, DApps, and Critical Online Services.
    :::
  :::

  ::: page-block {"className": "theme-container-6xl theme-margin-top-3 theme-padding-left-2 theme-padding-right-2", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-feature-grid {"columnsPerRow": 4, "textAlign": "center"}
      ::: feature
        icon: {"name": "Shield", "variant": "primary"}
        title: Cybersecurity Firms
        description: Protect clients from fake agents & attacks.
        link: { "caption": "Partner with Us", "url": "/partners" }
      :::
      ::: feature
        icon: {"name": "Code", "variant": "accent"}
        title: Developers
        description: Build apps with verifiable trust and secure delivery.
        link: { "caption": "Start Building", "url": "/developers" }
      :::
      ::: feature
        icon: {"name": "Building2", "variant": "green"}
        title: Businesses
        description: Secure your automation stack with trusted agents.
        link: { "caption": "Learn More", "url": "/businesses" }
      :::
      ::: feature
        icon: {"name": "Users", "variant": "purple"}
        title: Users
        description: Know when apps are verified and safe to use online.
        link: { "caption": "Get Protected", "url": "/users" }
      :::
    :::
  :::
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "alignItems": "center", "gap": "1.5rem"}
    ::: page-image {"width":"80px","height":"auto"}
    url: "/.assets/problem.png"
    :::

    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-2 theme-container-3xl"}
    ## The Exploding Challenge of ::gradient[Digital Trust]{color: {error}}
    :::

    ::: page-stack {"className": "theme-container-5xl", "direction": "horizontal", "alignItems": "center", "gap": "2rem", "mediaQueries": [{"maxWidth": "768px", "properties": {"direction": "vertical"}}]}
      ::: page-block {"className": "theme-stack-flex-1"}
        ::: page-text {"className": "theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
        The digital landscape is increasingly volatile, with sophisticated supply chain attacks and AI-driven phishing campaigns now routine. The rise of autonomous AI agents introduces an unprecedented challenge: verifying the authenticity and integrity of non-human actors. Traditional signature-based and perimeter defenses are no longer sufficient to secure interactions or ensure trust in this complex, interconnected future.
        :::
      :::
      ::: page-block {"className": "theme-error-bg theme-spacing-lg theme-stack-flex-1 theme-border-radius-lg", "width": "100%", "mediaQueries": [{"maxWidth": "767px", "properties": {"padding": {"left": "1rem", "right": "1rem", "top": "1rem", "bottom": "1rem"}}}]}
        ::: page-text {"className": "theme-text-lg-bold"}
        Critical Digital Threats
        :::
        ::: page-check-list {"icon": {"name": "AlertTriangle", "color": "{error}", "size": "1rem"}, "item": {"margin": "1rem 0"}}
          ::: item
            description: AI-Driven Phishing
          :::
          ::: item
            description: Supply Chain Attacks
          :::
          ::: item
            description: Agent Impersonation
          :::
          ::: item
            description: AI Agent Subversion
          :::
          ::: item
            description: Code Injection
          :::
        :::
      :::
    :::
  :::
:::


::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ## TrustRoot's ::gradient[Solution]{color: {primary}}
    :::
    ::: page-text {"className": "theme-text-xl-secondary", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    TrustRoot brings verifiable identity and integrity to your digital interactions by:
    :::
  :::

  ::: page-block {"className": "theme-container-7xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow":3, "textAlign": "left"}
      ::: feature
        icon: {"name": "Shield", "variant": "primary"}
        title: Verifying the Digital Frontline
        description: Ensuring the websites, DApps, and applications you use haven't been tampered with.
      :::
      ::: feature
        icon: {"name": "Server", "variant": "accent"}
        title: Securing Digital Backbones
        description: Guaranteeing the integrity and confidentiality of service backends and agent logic.
      :::
      ::: feature
        icon: {"name": "Bot", "variant": "purple"}
        title: Building an Authentic Agent Ecosystem
        description: Enabling autonomous agents to identify and trust each other, preventing imposters and subversion.
      :::
    :::
  :::
:::

::: page-block {"className": "theme-container-7xl theme-margin-bottom-5", "align": "center"}
  ::: page-stack {"align": "center", "direction": "horizontal", "mediaQueries": [{"maxWidth": "768px", "properties": {"direction": "vertical"}}]}
    ::: page-stack {"gap": "1.5rem", "alignItems": "flex-end", "justifyContent": "center", "mediaQueries": [{"maxWidth": "767px", "properties": {"alignItems": "center"}}]}
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1.5rem"}
        ::: page-text
        AI-Driven Phishing
        :::
        ::: page-stack {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
          ::: page-text {"width": "2rem", "border": {"width": "2px"}}
          ---
          :::
          ::: page-icon {"name": "ArrowRight", "size": "var(--font-size-lg)"}
          :::
        :::
      :::
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1.5rem"}
        ::: page-text
        Supply Chain Attacks
        :::
        ::: page-stack {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
          ::: page-text {"width": "2rem", "border": {"width": "2px"}}
          ---
          :::
          ::: page-icon {"name": "ArrowRight", "size": "var(--font-size-lg)"}
          :::
        :::
      :::
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1.5rem"}
        ::: page-text
        DNS Hijacking
        :::
         ::: page-stack {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
          ::: page-text {"width": "2rem", "border": {"width": "2px"}}
          ---
          :::
          ::: page-icon {"name": "ArrowRight", "size": "var(--font-size-lg)"}
          :::
        :::
      :::
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1.5rem"}
        ::: page-text
        AI Agent Subversion
        :::
        ::: page-stack {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
          ::: page-text {"width": "2rem", "border": {"width": "2px"}}
          ---
          :::
          ::: page-icon {"name": "ArrowRight", "size": "var(--font-size-lg)"}
          :::
        :::
      :::
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1.5rem"}
        ::: page-text
        Code Injection
        :::
        ::: page-stack {"direction": "horizontal", "gap": "0.5rem", "alignItems": "center"}
          ::: page-text {"width": "2rem", "border": {"width": "2px"}}
          ---
          :::
          ::: page-icon {"name": "ArrowRight", "size": "var(--font-size-lg)"}
          :::
        :::
      :::
    :::
    ::: page-image {"width": "340px"}
    url: "/.assets/trustroot-logo.png"
    :::
  :::
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "alignItems": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ## Secure Your Stake in the ::gradient[Digital Future]{className: theme-gradient-primary}
    :::
    ::: page-text {"className": "theme-text-xl-secondary theme-container-3xl", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Our comprehensive trust protocol serves multiple stakeholders, each with unique needs and benefits in the digital security ecosystem.
    :::
  :::

  ::: page-block {"className": "theme-container-7xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 2, "textAlign": "left"}
      ::: feature
        icon: {"name": "Building2", "variant": "primary"}
        title: Cybersecurity Firms
        description: Elevate your portfolio with the foundational protocol for AI agent security and next-gen digital trust
        link: { "caption": "For Cybersecurity Firms: Partner with Us", "url": "/partners" }
      :::
      ::: feature
        icon: {"name": "Code", "variant": "accent"}
        title: Developers
        description: Integrate unparalleled trust into your DApps, services, and cutting-edge AI agent designs
        link: { "caption": "Explore Developer Resources", "url": "/developers" }
      :::
      ::: feature
        icon: {"name": "Users", "variant": "green"}
        title: Organizations/Businesses
        description: Future-proof your operations by ensuring authentic online interactions and trusted AI automation
        link: { "caption": "Discover TrustRoot for Enterprises", "url": "/businesses" }
      :::
      ::: feature
        icon: {"name": "Globe", "variant": "purple"}
        title: General Public/Users
        description: Empower your digital safety: Verify every online interaction
        link: { "caption": "How TrustRoot Protects You", "url": "/users" }
      :::
    :::
  :::
:::

::: page-section {"className": "theme-gradient-primary-to-right"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "1.5rem"}
    ::: page-text {"className": "theme-text-white", "textAlign":"center"}
    ### Ready to Build a Verifiably Trusted Digital Future?
    :::
    ::: page-text {"className": "theme-text-xl-white theme-margin-bottom-1", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Join the revolution in digital trust. Whether you're a security professional, developer, or organization looking to protect your digital interactions, TrustRoot has the solution for you.
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Get in Touch
        url: /contact
        variant: foreground
        icon: Mail
        rightIcon: ArrowRight
      :::
      ::: button
        caption: Read Our Whitepaper
        url: https://docs.trustroot.org
        variant: outline
        icon: BookOpen
        rightIcon: ArrowRight
      :::
      ::: button
        caption: Explore the Blog
        url: /blog
        variant: outline
        icon: Newspaper
        rightIcon: ArrowRight
      :::
    :::
  :::
:::
