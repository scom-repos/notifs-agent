::: var
primary: --color-primary-main
secondary: --color-secondary
accent: --color-accent-main
purple: --color-purple-main
green: --color-green-main
error: --color-error-main
warning: --color-warning-main
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
:::

::: page-section {"className": "theme-gradient-bottom-right-dark theme-spacing-hero"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "gap": "var(--spacing-gap)", "alignItems": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-1 theme-text-white"}
    # How TrustRoot ::gradient[Actually Works]{className: theme-gradient-accent-to-primary-text}
    :::
    ::: page-block {"className": "theme-container-3xl theme-margin-bottom-3", "align": "center"}
      ::: page-text {"textAlign":"center", "className": "theme-text-light-gray theme-text-2xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
      TrustRoot goes beyond traditional security, offering a foundational set of capabilities that establish and verify authenticity across your entire digital landscape. We help you move from reactive defense to proactive, verifiable trust.
      :::
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: View Technical Documentation
        icon: Users
        url: https://docs.trustroot.org
        variant: foreground
        rightIcon: ArrowRight
      :::
    :::
  :::
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-3", "gap": "1rem", "align": "center"}
    ::: page-text {"textAlign": "center"}
    ### TrustRoot Key Features
    :::
    ::: page-text {"className": "theme-text-xl-secondary", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Building Verifiable Trust From Code to Interaction
    :::
  :::

  ::: page-block {"className": "theme-container-5xl", "align": "center"}
    ::: page-tabs {"justifyContent": "center", "border": {"width": 0}, "tab": {"border": {"radius": "0.5rem"}, "margin": {"bottom": "1rem", "left": "0.5rem"}}}
      ::: tab {"active": {"background": {"color": "{primary}"}, "transform": "scale(1.05)", "font": {"color": "#fff"}}}
        title: Verifiable Application & Agent Integrity
        tabKey: tab-1
        icon: Shield
        ::: page-block {"className": "theme-spacing-lg theme-border-radius-2xl theme-background-bg theme-box-shadow-xl"}
          ::: page-stack {"direction": "horizontal", "gap": "1rem", "alignItems": "center"}
            ::: page-block {"className": "theme-icon-wrapper theme-icon-primary", "width": "3.5rem", "height": "3.5rem"}
              ::: page-icon {"name": "Shield", "size": "2rem", "color": "#fff"}
              :::
            :::
            ::: page-text {"font":{"size":"var(--font-size-xl)","weight":"bold"}}
            Verifiable Application & Agent Integrity
            :::
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1 theme-margin-top-2"}
          Overview
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          We ensure that the websites, DApps, and AI agents you and your users interact with are the real deal and haven't been tampered with or compromised.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          How It Works
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          TrustRoot cryptographically verifies the code and assets of your applications and agents against immutable records, preventing phishing, DNS hijacking, and malicious code injection on the client-side.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          Benefits
          :::
          ::: page-text {"className": "theme-text-secondary"}
          Protects your users and your brand from fraudulent impersonation and ensures a genuine digital experience.
          :::
        :::
      :::
      ::: tab {"active": {"background": {"color": "{green}"}, "transform": "scale(1.05)", "font": {"color": "#fff"}}}
        title: Secure, Trusted Execution Environments (TEEs)
        tabKey: tab-2
        icon: Server
        ::: page-block {"className": "theme-spacing-lg theme-border-radius-2xl theme-background-bg theme-box-shadow-xl"}
          ::: page-stack {"direction": "horizontal", "gap": "1rem", "alignItems": "center"}
            ::: page-block {"className": "theme-icon-wrapper theme-icon-green", "width": "3.5rem", "height": "3.5rem"}
              ::: page-icon {"name": "Server", "size": "2rem", "color": "#fff"}
              :::
            :::
            ::: page-text {"font":{"size":"var(--font-size-xl)","weight":"bold"}}
            Secure, Trusted Execution Environments (TEEs)
            :::
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1 theme-margin-top-2"}
          Overview
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          We provide a shielded space where your critical backend logic, sensitive data, and AI agent decision-making processes can run with guaranteed confidentiality and integrity.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          How It Works
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          TrustRoot leverages hardware-backed Trusted Execution Environments (TEEs) to create isolated, tamper-proof computing environments for your servers, DApp backends, and autonomous AI agents.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          Benefits
          :::
          ::: page-text {"className": "theme-text-secondary"}
          Safeguards your core operations from internal and external threats, even if the underlying operating system is compromised.
          :::
        :::
      :::
      ::: tab {"active": {"background": {"color": "{warning}"}, "transform": "scale(1.05)", "font": {"color": "#fff"}}}
        title: Secure Software Supply Chain Protection
        tabKey: tab-3
        icon: Package
        ::: page-block {"className": "theme-spacing-lg theme-border-radius-2xl theme-background-bg theme-box-shadow-xl"}
          ::: page-stack {"direction": "horizontal", "gap": "1rem", "alignItems": "center"}
            ::: page-block {"className": "theme-icon-wrapper theme-icon-warning", "width": "3.5rem", "height": "3.5rem"}
              ::: page-icon {"name": "Package", "size": "2rem", "color": "#fff"}
              :::
            :::
            ::: page-text {"font":{"size":"var(--font-size-xl)","weight":"bold"}}
            Secure Software Supply Chain Protection
            :::
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1 theme-margin-top-2"}
          Overview
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          We protect your software from vulnerabilities introduced at any stage, from development to deployment.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          How It Works
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          TrustRoot integrates into your build and deployment pipelines, attesting to the integrity of code, dependencies, and build processes. This ensures that only verified, untampered software ever reaches production or your customers.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          Benefits
          :::
          ::: page-text {"className": "theme-text-secondary"}
          Prevents devastating supply chain attacks, reducing your exposure to malicious code injection and ensuring the provenance of your digital assets.
          :::
        :::
      :::
      ::: tab {"active": {"background": {"color": "{purple}"}, "transform": "scale(1.05)", "font": {"color": "#fff"}}}
        title: Transparent Integrity Verification (TrustRoot Explorer)
        tabKey: tab-4
        icon: Bot
        ::: page-block {"className": "theme-spacing-lg theme-border-radius-2xl theme-background-bg theme-box-shadow-xl"}
          ::: page-stack {"direction": "horizontal", "gap": "1rem", "alignItems": "center"}
            ::: page-block {"className": "theme-icon-wrapper theme-icon-purple", "width": "3.5rem", "height": "3.5rem"}
              ::: page-icon {"name": "Bot", "size": "2rem", "color": "#fff"}
              :::
            :::
            ::: page-text {"font":{"size":"var(--font-size-xl)","weight":"bold"}}
            Transparent Integrity Verification (TrustRoot Explorer)
            :::
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1 theme-margin-top-2"}
          Overview
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          A public, easy-to-use platform that allows anyone to check the integrity status of TrustRoot-compliant services.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          How It Works
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          If a registered DApp or online service is detected as compromised (e.g., tampered frontend, DNS hijacked), TrustRoot automatically flags it on the TrustRoot Explorer site.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          Benefits
          :::
          ::: page-text {"className": "theme-text-secondary"}
          Provides an independent, accessible way for users, partners, and the public to verify trust, adding a crucial layer of transparency and delivering rapid threat intelligence across the ecosystem.
          :::
        :::
      :::
      ::: tab {"active": {"background": {"color": "{purple}"}, "transform": "scale(1.05)", "font": {"color": "#fff"}}}
        title: Multi-Registry Support (EAS & Nostr)
        tabKey: tab-5
        icon: Users
        ::: page-block {"className": "theme-spacing-lg theme-border-radius-2xl theme-background-bg theme-box-shadow-xl"}
          ::: page-stack {"direction": "horizontal", "gap": "1rem", "alignItems": "center"}
            ::: page-block {"className": "theme-icon-wrapper theme-icon-purple", "width": "3.5rem", "height": "3.5rem"}
              ::: page-icon {"name": "Users", "size": "2rem", "color": "#fff"}
              :::
            :::
            ::: page-text {"font":{"size":"var(--font-size-xl)","weight":"bold"}}
            Multi-Registry Support (EAS & Nostr)
            :::
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1 theme-margin-top-2"}
          Overview
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          Flexibility in how digital identities and integrity attestations are registered and verified.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          How It Works
          :::
          ::: page-text {"className": "theme-text-secondary theme-margin-bottom-2"}
          TrustRoot utilizes robust blockchain-based registries like the Ethereum Attestation Service (EAS) for high-assurance, immutable records, complemented by a Nostr-based registry for potentially lower-cost and more flexible attestation options.
          :::
          ::: page-text {"className": "theme-text-lg-bold theme-margin-bottom-1"}
          Benefits
          :::
          ::: page-text {"className": "theme-text-secondary"}
          Offers choice and scalability for registering your applications and agents, adapting to different use cases and cost considerations. (Note: During Phase 1, TrustRoot will manage registrations for simplicity).
          :::
        :::
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-3", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### Built on Proven Technologies
    :::
    ::: page-text {"className": "theme-text-xl-secondary", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    TrustRoot leverages industry-standard cryptographic primitives and trusted hardware to deliver uncompromising security.
    :::
  :::

  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-lg)"}
    ::: page-feature-grid {"preset": "--component-feature-noBorder", "textAlign": "center", "hover": {"background": {"color": "--color-secondary"}}}
      ::: feature
        title: Ethereum Attestation Service (EAS)
        description: Immutable, on-chain attestations for trust anchoring
      :::
      ::: feature
        description: Creating verifiable, timestamped records of application and agent authenticity
      :::
    :::

    ::: page-feature-grid {"preset": "--component-feature-noBorder", "textAlign": "center", "hover": {"background": {"color": "--color-secondary"}}}
      ::: feature
        title: Intel SGX & AWS Nitro
        description: Trusted Execution Environments for secure computation
      :::
      ::: feature
        description: Running critical backend logic with hardware-level integrity guarantees
      :::
    :::

    ::: page-feature-grid {"preset": "--component-feature-noBorder", "textAlign": "center", "hover": {"background": {"color": "--color-secondary"}}}
      ::: feature
        title: Cryptographic Signatures
        description: Ed25519 and ECDSA signatures for verification
      :::
      ::: feature
        description: Signing code, deployments, and agent communications for authenticity
      :::
    :::

    ::: page-feature-grid {"preset": "--component-feature-noBorder", "textAlign": "center", "hover": {"background": {"color": "--color-secondary"}}}
      ::: feature
        title: Zero-Knowledge Proofs
        description: Privacy-preserving verification mechanisms
      :::
      ::: feature
        description: Enabling verification without revealing sensitive implementation details
      :::
    :::
  :::
:::

::: page-section {"className": "theme-gradient-bottom-right-dark"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "1.5rem"}
    ::: page-text {"className": "theme-text-white", "textAlign":"center"}
    ### Ready to Implement TrustRoot?
    :::
    ::: page-text {"textAlign":"center", "className": "theme-margin-bottom-1 theme-text-xl-white", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Whether you're a developer looking to integrate our SDK or a business exploring partnership opportunities, we're here to help you build with trust.
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Dive Deeper into Our Whitepaper
        icon: Book
        url: https://docs.trustroot.org
        variant: outline
      :::
    :::
  :::
:::
