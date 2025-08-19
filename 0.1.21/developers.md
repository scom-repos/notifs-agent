::: var
primary: var(--color-primary-main)
accent: var(--color-accent-main)
warning: var(--color-warning-main)
error: var(--color-error-main)
purple: var(--color-purple-main)
green: var(--color-green-main)
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
    color: "#2563eb"
  accent:
    color: "#0d968b"
  warning:
    color: "#f97316"
  purple:
    color: "#8b5cf6"
  green:
    color: "#16a249"
  error:
    color: "#ef4444"
:::

::: page-section {"className": "theme-gradient-primary-to-accent theme-spacing-hero"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "alignItems": "center"}
    ::: page-text {"className": "theme-margin-bottom-2 theme-text-white", "textAlign": "center"}
    # Build with Trust: Integrate TrustRoot into Your ::gradient[DApps, Services & Agent Architectures]{className: theme-gradient-primary-to-accent-text}
    :::
    ::: page-text {"className": "theme-text-2xl theme-text-light-gray theme-margin-bottom-3", "maxWidth": "var(--container-3xl)", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
    Frontend supply chain attacks are escalating. How do you guarantee the integrity of your deployed code?
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Get Started with SDK
        icon: Code
        variant: foreground
        url: https://github.com/trustRootOrg/sdk
      :::
      ::: button
        caption: View Documentation
        icon: Book
        variant: accent
        url: https://docs.trustroot.org
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### How TrustRoot Works for Developers
    :::
    ::: page-text {"textAlign": "center", "className": "theme-text-xl theme-text-secondary theme-margin-bottom-4", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    A comprehensive approach to verifiable trust across your entire application stack
    :::
  :::
  
  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 3, "textAlign": "center"}
      ::: feature
        icon: {"name": "Puzzle", "variant": "primary"}
        title: Client-Side Verification
        description: Automatically verify frontend code integrity against immutable records before execution.
      :::
      
      ::: feature
        icon: {"name": "Lock", "variant": "purple"}
        title: Backend Integrity
        description: Secure your backend services within Trusted Execution Environments (TEEs).
      :::
      
      ::: feature
        icon: {"name": "Shield", "variant": "accent"}
        title: Deployment Security
        description: Integrate seamlessly into your CI/CD pipeline for continuous attestation.
      :::
    :::
  :::
    
  ::: page-block {"preset": "--component-card-default", "className": "theme-container-4xl theme-margin-top-4", "background": {"color": "#111827"}}
    ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "0.5rem"}
      ::: page-icon {"name": "Terminal", "color": "#fff", "size": "1.25rem"}
      :::
      ::: page-text {"className": "theme-text-white"}
      Quick Integration Example
      :::
    :::
    ::: page-block {"background": {"color": "#111827"}, "className": "theme-margin-top-1", "gap": "1rem"}
      ::: page-text {"className": "theme-text-light-gray theme-text-sm", "font": {"name": "monospace"}}
      // Install TrustRoot SDK
      :::
      ::: page-text {"className": "theme-text-green theme-text-sm", "font": {"name": "monospace"}}
      npm install @trustroot/sdk
      :::
      ::: page-text {"className": "theme-text-light-gray theme-text-sm", "font": {"name": "monospace"}}
      // Initialize in your app
      :::
      ::: page-text {"className": "theme-text-green theme-text-sm", "font": {"name": "monospace"}}
      import { TrustRoot } from '@trustroot/sdk';
      :::
      ::: page-text {"className": "theme-text-green theme-text-sm", "font": {"name": "monospace"}}
      import { Wallet } from '@ijstech/eth-wallet';
      :::
      ::: page-text {"className": "theme-text-green theme-text-sm", "font": {"name": "monospace"}}
      import * as dotenv from 'dotenv';
      :::
      ::: page-text {"className": "theme-text-green theme-text-sm", "font": {"name": "monospace"}}
      dotenv.config();
      :::
      ::: page-text {"className": "theme-text-green theme-text-sm", "font": {"name": "monospace"}}
      const wallet = new Wallet(process.env.RPC_URL!, { privateKey: process.env.PRIVATE_KEY! });
      :::
      ::: page-text {"className": "theme-text-green theme-text-sm", "font": {"name": "monospace"}}
      const sdk = new SDK(wallet);
      :::
    :::
  :::
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### Key Features
    :::
    ::: page-text {"textAlign": "center", "className": "theme-text-xl theme-text-secondary theme-margin-bottom-4", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Everything you need to build secure, verifiable applications
    :::
  :::
    
  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 3, "textAlign": "left"}
      ::: feature
        icon: {"name": "Puzzle"}
        title: Easy Integration with Web3 Frameworks
        description: Drop-in integration with popular Web3 frameworks like Hardhat, Foundry, and Truffle for seamless development workflow.
      :::
      
      ::: feature
        icon: {"name": "Lock"}
        title: Seamless TEE Integration
        description: Built-in support for Intel SGX, AWS Nitro, and Azure Confidential Computing with zero configuration required.
      :::
      
      ::: feature
        icon: {"name": "Code"}
        title: Robust APIs and SDKs
        description: Comprehensive SDKs with type safety, extensive documentation, and code examples across multiple programming languages.
      :::
      
      ::: feature
        icon: {"name": "Shield"}
        title: Reduced Attack Surface
        description: Proactive security measures with runtime integrity checks and supply chain protection to minimize vulnerabilities.
      :::
      
      ::: feature
        icon: {"name": "Users"}
        title: Enhanced User Trust
        description: Build applications that users can trust with verifiable security proofs and transparent integrity verification.
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### Developer Use Cases
    :::
    ::: page-text {"textAlign": "center", "className": "theme-text-xl theme-text-secondary theme-margin-bottom-4", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Real-world applications across different development scenarios
    :::
  :::

  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 3, "textAlign": "center"}
      ::: feature
        icon: {"name": "Shield", "variant": "primary"}
        title: DApp Security
        description: Protect your decentralized applications from phishing and supply chain attacks.
        ::: page-check-list {"type":"unordered", "description": {"className": "theme-text-sm theme-text-secondary", "lineHeight": "1"},"icon": {"size": "var(--font-size-sm)"}, "item": {"margin": "0.5rem 0"}}
          ::: item
            description: Smart contract interaction verification
          :::
          ::: item
            description: Wallet connection security
          :::
          ::: item
            description: Frontend integrity checks
          :::
        :::
      :::
      
      ::: feature
        icon: {"name": "Users", "variant": "purple"}
        title: Agent Architectures
        description: Build autonomous agents that can verify and trust each other
        ::: page-check-list {"type":"unordered", "description": {"className": "theme-text-sm theme-text-secondary", "lineHeight": "1"},"icon": {"size": "var(--font-size-sm)"}, "item": {"margin": "0.5rem 0"}}
          ::: item
            description:  Multi-agent system security
          :::
          ::: item
            description: AI model deployment verification
          :::
          ::: item
            description: Agent identity management
          :::
        :::
      :::
      
      ::: feature
        icon: {"name": "Lock", "variant": "accent"}
        title: Backend Services
        description: Ensure the integrity and confidentiality of your service backends
        ::: page-check-list {"type":"unordered", "description": {"className": "theme-text-sm theme-text-secondary", "lineHeight": "1"},"icon": {"size": "var(--font-size-sm)"}, "item": {"margin": "0.5rem 0"}}
          ::: item
            description: API endpoint verification
          :::
          ::: item
            description: Database integrity checks,
          :::
          ::: item
            description: Microservice authentication
          :::
        :::
      :::
    :::
  :::
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### Documentation & Resources
    :::
    ::: page-text {"textAlign": "center", "className": "theme-text-xl theme-text-secondary theme-margin-bottom-4", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Everything you need to get started and build with confidence
    :::
  :::
    
  ::: page-block {"className": "theme-container-6xl", "width": "100%", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 2, "textAlign": "left"}
      ::: feature
        icon: {"name": "Book"}
        title: Technical Documentation
        description: In-depth guides, API references, and protocol specifications
        link: {"url": "https://docs.trustroot.org", "caption": "View Documentation"}
      :::
      
      ::: feature
        icon: {"name": "Github"}
        title: Open Source SDKs
        description: Explore our open source tools, examples, and contribute
        link: {"url": "https://github.com/trustRootOrg/sdk", "caption": "View on GitHub"}
      :::
      
      ::: feature
        icon: {"name": "FileCode"}
        title: Example Projects
        description: Sample DApps and agent implementations using TrustRoot
        link: {"url": "https://github.com/trustRootOrg/guarded-demo", "caption": "View Examples"}
      :::
      
      ::: feature
        icon: {"name": "MessageCircle"}
        title: Developer Community
        description: Join our Telegram Group for support, discussions, and collaboration
        link: {"url": "https://Telegram Group.gg/trustroot", "caption": "Join Community"}
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### Frequently Asked Questions
    :::
    ::: page-text {"textAlign": "center", "className": "theme-text-secondary theme-margin-bottom-4"}
    Answers to the most frequently asked questions about TrustRoot
    :::
    
    ::: page-block {"gap": "2rem", "className": "theme-container-4xl", "align": "center"}
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-primary-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Shield", "color": "{primary}", "size": "1rem"}
            :::
          :::

          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder"}
            Can I join the TrustRoot team?
            :::
            ::: page-text {}
            Yes! We're growing and need passionate people—developers to build, marketers to spread the word, or organizers to support our community. With the testnet live this month, it's an exciting time to join. Visit our Team page to apply and help shape a safer digital future!
            :::
          :::
        :::
      :::

      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-purple-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Coins", "color": "{purple}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder"}
            What is the native $TROOT token?
            :::
            ::: page-text {}
            The native $TROOT token powers our ecosystem, rewarding developers for building and certifying safe apps, much like farmers earn through organic certification. It incentivizes trust and growth, with 40% allocated for community use. Launched with our testnet this month, learn more in our documentation!
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-accent-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Code", "color": "{accent}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder"}
            How can developers get started?
            :::
            ::: page-text {}
            Visit our About page for the big picture, the Developer Hub for building, or [Docs](https://docs.trustroot.org) for technical deep dives. Contact us at contact@trustroot.org or join our Telegram group for real-time support. With the testnet ongoing, we're here to help you engage!
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-green-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Globe", "color": "{green}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder"}
            How does TrustRoot scale for global use?
            :::
            ::: page-text {}
            Like a 'Certified Organic' label scaling worldwide with digital validation, TrustRoot uses blockchain and immutable registries to handle millions of interactions. Our testnet, live this month, is already scaling with early adopters, and pilots in Q4 2025 will expand our reach. See the tech behind it on documentation!
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-warning-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "MessageCircle", "color": "{warning}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder"}
            How can I learn more or get support?
            :::
            ::: page-text {}
            Visit our About page for the big picture, the Developer Hub for building, or [Docs](https://docs.trustroot.org) for technical deep dives. Contact us at contact@trustroot.org or join our Telegram Group for real-time support. With the testnet ongoing, we're here to help you engage!
            :::
          :::
        :::
      :::
    :::
  :::
:::

::: page-section {"className": "theme-gradient-primary-to-accent"}
  ::: page-block {"className": "theme-container-4xl", "align": "center", "gap": "1.5rem"}
    ::: page-text {"className": "theme-text-white", "textAlign": "center"}
    ### Ready to Build Secure Applications?
    :::
    ::: page-text {"className": "theme-text-xl theme-text-light-gray theme-margin-bottom-1", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Start integrating TrustRoot today and give your users the trust they deserve
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Get Started with SDK
        icon: Code
        variant: foreground
        url: https://github.com/trustRootOrg/sdk
      :::
      ::: button
        caption: View Documentation
        icon: Book
        variant: outline
        url: https://docs.trustroot.org
      :::
    :::
  :::
::: 