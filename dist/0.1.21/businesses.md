::: var
primary: var(--color-primary-main)
accent: var(--color-accent-main)
warning: var(--color-warning-main)
error: var(--color-error-main)
purple: var(--color-purple-main)
green: var(--color-green-main)
secondary: var(--color-secondary)
textSecondary: var(--color-text-secondary)
padding: {"top": "2rem", "bottom": "2rem", "left": "2rem", "right": "2rem"}
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
  dark:
    backgroundColor: "#000"
    color: "#fff"
    border: "1px solid #000"
    borderRadius: "8px"
    padding: "0.75rem 2rem"
    fontSize: "1.125rem"
    fontWeight: 600
:::

::: page-section {"className": "theme-gradient-primary-to-accent theme-spacing-hero"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "alignItems": "center"}
    ::: page-text {"className": "theme-margin-bottom-2 theme-text-white", "textAlign": "center"}
    # TrustRoot for Enterprises: ::gradient[Unbreakable Trust]{color: #bbf7d0} for Your Digital Operations and AI Future
    :::
    ::: page-text {"textAlign":"center", "className": "theme-margin-bottom-3 theme-text-2xl theme-text-light-green theme-container-3xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
    Secure your critical applications, supply chains, and autonomous agents from the core, ensuring verifiable integrity and protecting your brand.
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Request a Demo
        icon: Users
        variant: primary
        url: /contact
        rightIcon: ArrowRight
      :::
      ::: button
        caption: Download Enterprise Brief
        variant: foreground
        url: #
        rightIcon: ArrowRight
    :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-stack {"direction": "horizontal", "gap": "4rem", "alignItems": "center", "mediaQueries": [{"maxWidth": "768px", "properties": {"direction": "vertical", "gap": "1rem"}}]}
      ::: page-block {"className": "theme-stack-flex-1"}
        ::: page-text {"className": "theme-margin-bottom-1 theme-text-bolder theme-text-4xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-2xl"}}}]}
        The Enterprise Challenge
        :::
        ::: page-text {"lineHeight": "1.75rem", "className": "theme-margin-bottom-2 theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
        TrustRoot offers cybersecurity firms a unique opportunity to lead in the emerging AI security market by providing the foundational protocol for verifiable AI Agent and service authenticity, enabling them to offer critical auditing services and meet enterprise demand for trusted autonomous interactions. This partnership positions firms at the forefront of securing the future's digital landscape.
        :::
      :::
      
      ::: page-block {"className": "theme-card-secondary-bg theme-stack-flex-1", "border": {"radius": "var(--borderRadius-xl)"}, "width": "100%", "mediaQueries": [{"maxWidth": "767px", "properties": {"padding": {"left": "1rem", "right": "1rem"}}}]}
        ::: page-text {"className": "theme-margin-bottom-075 theme-text-xl-bold"}
        Enterprise Impact
        :::
        ::: page-text {"font": {"size": "2rem", "weight": "700", "color": "{error}"}, "className": "theme-margin-bottom-1"}
        $4.45M
        :::
        ::: page-text {"className": "theme-text-sm-secondary"}
        Average cost of a data breach
        :::
        ::: page-text {"font": {"size": "2rem", "weight": "700", "color": "{warning}"}, "className": "theme-margin-bottom-1"}
        300%
        :::
        ::: page-text {"className": "theme-text-sm-secondary"}
        Increase in supply chain attacks
        :::
        ::: page-text {"font": {"size": "2rem", "weight": "700", "color": "#ca8a04"}, "className": "theme-margin-bottom-1"}
        83%
        :::
        ::: page-text {"className": "theme-text-sm-secondary"}
        Of organizations experienced phishing
        :::
        ::: page-text {"font": {"size": "2rem", "weight": "700", "color": "{primary}"}, "className": "theme-margin-bottom-1"}
        AI Era
        :::
        ::: page-text {"className": "theme-text-sm-secondary"}
        New agent-based threats emerging
        :::
      :::
    :::
  :::
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-1"}
    ### How TrustRoot Helps
    :::
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-4 theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Comprehensive solutions that address the full spectrum of enterprise digital trust challenges
    :::
  :::
    
  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 3, "textAlign": "left"}
      ::: feature
        icon: {"name": "Shield"}
        title: End-to-End Verifiable Trust
        description: TrustRoot provides authenticity across frontend, backend, and entire software lifecycles, ensuring every digital touchpoint is cryptographically verifiable.
      :::
      
      ::: feature
        icon: {"name": "Lock"}
        title: Supply Chain Security
        description: Protection against malicious code injection from development to deployment, securing your software supply chain at every stage.
      :::
      
      ::: feature
        icon: {"name": "Bot"}
        title: AI Agent Integrity
        description: TrustRoot ensures the authenticity and trustworthiness of autonomous AI agents within your operations, preventing agent subversion and impersonation.
      :::
      
      ::: feature
        icon: {"name": "TrendingUp"}
        title: Reduced Risk & Compliance
        description: Mitigate financial, reputational, and regulatory risks with verifiable security measures and compliance support.
      :::
      
      ::: feature
        icon: {"name": "CheckCircle"}
        title: Operational Resilience
        description: Verifiable trust leads to more robust and reliable systems, reducing downtime and ensuring business continuity.
      :::
      
      ::: feature
        icon: {"name": "ArrowRight"}
        title: Future-Proofing
        description: Position your organization to safely adopt advanced technologies like AI automation with a foundation of verifiable trust.
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-1"}
    ### Why TrustRoot?
    :::
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-4 theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    The foundational advantages that set TrustRoot apart
    :::
  :::
        
  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 3, "textAlign": "center"}
      ::: feature
        icon: {"name": "CheckCircle", "color": "{green}"}
        title: Foundational Protocol
        description: Not just another security product—TrustRoot is a fundamental layer of trust.
      :::
      
      ::: feature
        icon: {"name": "CheckCircle", "color": "{green}"}
        title: Proactive Defense
        description: Moving beyond reactive security to verifiable authenticity.
      :::
      
      ::: feature
        icon: {"name": "CheckCircle", "color": "{green}"}
        title: Future-Oriented
        description: Designed for the emerging AI agent landscape and tomorrow's digital challenges.
      :::
    :::
  :::
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-1"}
    ### Team & Vision
    :::
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-4 theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Backed by industry leaders in AI security, enterprise systems, and protocol development, TrustRoot is building the foundation for trusted autonomous interactions
    :::
  :::
  
  ::: page-block {"className": "theme-container-6xl", "align": "center", "width": "100%"}
    ::: page-stack {"direction": "horizontal", "gap": "3rem", "alignItems": "center", "mediaQueries": [{"maxWidth": "768px", "properties": {"direction": "vertical"}}]}
      ::: page-block {"className": "theme-stack-flex-1"}
        ::: page-text {"className": "theme-margin-bottom-2 theme-text-2xl-bold"}
        Core Expertise
        :::
        ::: page-stack {"direction": "horizontal", "gap": "1rem", "wrap": "wrap"}
          ::: page-block {"className": "theme-spacing-padding theme-background-bg theme-border theme-box-shadow-md", "maxWidth": "250px", "mediaQueries": [{"maxWidth": "767px", "properties": {"maxWidth": "100%", "width": "100%"}}]}
            ::: page-stack {"direction": "horizontal", "gap": "1.5rem"}
              ::: page-block {"className": "theme-stack-flex-0"}
                ::: page-icon {"name": "Shield", "color": "{primary}", "size": "20px"}
                :::
              :::
              ::: page-block {"gap": "0.75rem"}
                ::: page-block {"preset": "--component-badge-default", "background": {"color": "{primary}"}}
                  ::: page-text {"className": "theme-text-sm-bold theme-text-white"}
                  Core Focus
                  :::
                :::
                ::: page-text {"className": "theme-text-sm-bold"}
                AI Security Innovation
                :::
                ::: page-text {"className": "theme-text-sm-secondary"}
                Pioneering secure frameworks for autonomous systems and AI agents
                :::
              :::
            :::
          :::
          
          ::: page-block {"className": "theme-spacing-padding theme-background-bg theme-border theme-box-shadow-md", "maxWidth": "250px", "mediaQueries": [{"maxWidth": "767px", "properties": {"maxWidth": "100%", "width": "100%"}}]}
            ::: page-stack {"direction": "horizontal", "gap": "1.5rem"}
              ::: page-block {"className": "theme-stack-flex-0"}
                ::: page-icon {"name": "Building2", "color": "{accent}", "size": "20px"}
                :::
              :::
              ::: page-block {"gap": "0.75rem"}
                ::: page-block {"preset": "--component-badge-default", "background": {"color": "{accent}"}}
                  ::: page-text {"className": "theme-text-sm-bold theme-text-white"}
                  Enterprise
                  :::
                :::
                ::: page-text {"className": "theme-text-sm-bold"}
                Enterprise Security
                :::
                ::: page-text {"className": "theme-text-sm-secondary"}
                Deep expertise in enterprise-grade security architecture and TEE implementation
                :::
              :::
            :::
          :::
          
          ::: page-block {"className": "theme-spacing-padding theme-background-bg theme-border theme-box-shadow-md", "maxWidth": "250px", "mediaQueries": [{"maxWidth": "767px", "properties": {"maxWidth": "100%", "width": "100%"}}]}
            ::: page-stack {"direction": "horizontal", "gap": "1.5rem"}
              ::: page-block {"className": "theme-stack-flex-0"}
                ::: page-icon {"name": "Code", "color": "{warning}", "size": "20px"}
                :::
              :::
              ::: page-block {"gap": "0.75rem"}
                ::: page-block {"preset": "--component-badge-default", "background": {"color": "{warning}"}}
                  ::: page-text {"className": "theme-text-sm-bold theme-text-white"}
                  Technical
                  :::
                :::
                ::: page-text {"className": "theme-text-sm-bold"}
                Protocol Development
                :::
                ::: page-text {"className": "theme-text-sm-secondary"}
                Leaders in verifiable trust protocols and distributed systems
                :::
              :::
            :::
          :::
          
          ::: page-block {"className": "theme-spacing-padding theme-background-bg", "border": {"radius": "var(--borderRadius-lg)", "width": "1px", "style": "solid", "color": "var(--color-border)"}, "boxShadow": "var(--shadow-md)", "maxWidth": "250px", "mediaQueries": [{"maxWidth": "767px", "properties": {"maxWidth": "100%", "width": "100%"}}]}
            ::: page-stack {"direction": "horizontal", "gap": "1.5rem"}
              ::: page-block {"className": "theme-stack-flex-0"}
                ::: page-icon {"name": "Award", "color": "{textSecondary}", "size": "20px"}
                :::
              :::
              ::: page-block {"gap": "0.75rem"}
                ::: page-block {"preset": "--component-badge-default","className": "theme-muted-bg"}
                  ::: page-text {"className": "theme-text-sm-bold theme-text-white"}
                  Standards
                  :::
                :::
                ::: page-text {"className": "theme-text-sm-bold"}
                Industry Standards
                :::
                ::: page-text {"className": "theme-text-sm-secondary"}
                Active contributors to EAS and TEE security standards
                :::
              :::
            :::
          :::
        :::
      :::
      
      ::: page-block {"className": "theme-stack-flex-1"}
        ::: page-block {"preset": "--component-card-gradientPrimary", "alignItems": "center", "justifyContent": "center", "gap": "0.5rem"}
          ::: page-icon {"name": "Target", "color": "{primary}", "size": "3rem"}
          :::
          ::: page-text {"className": "theme-text-xl-bold"}
          Our Vision
          :::
          ::: page-text {"font": {"size": "var(--font-size-md)", "color": "{textSecondary}"}, "lineHeight": "1.6", "textAlign": "center"}
          To establish the global standard for AI agent verification and autonomous system security, enabling a future where organizations can confidently deploy and interact with AI systems at scale while maintaining complete trust and control.
          :::
        :::
      :::
    :::
  :::
:::

::: page-section {"className": "theme-gradient-primary-to-accent"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "1.5rem"}
    ::: page-text {"className": "theme-text-white", "textAlign": "center"}
    ### Ready to Future-Proof Your Enterprise?
    :::
    ::: page-text {"textAlign":"center", "className": "theme-margin-bottom-1 theme-text-light-cyan theme-text-xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Join forward-thinking enterprises that are building unbreakable trust into their digital operations. Secure your organization's future with TrustRoot.
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Speak to our Enterprise Solutions Team
        rightIcon: ArrowRight
        variant: dark
        url: /contact
      :::
      ::: button
        caption: Download Enterprise Brief
        variant: outline
        url: #
      :::
    :::
  :::
::: 