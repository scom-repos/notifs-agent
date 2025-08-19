::: var
primary: var(--color-primary-main)
accent: var(--color-accent-main)
warning: var(--color-warning-main)
error: var(--color-error-main)
purple: var(--color-purple-main)
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
    borderRadius: "8px"
    backgroundColor: --color-primary-light
  accent:
    color: "#0d968b"
    borderRadius: "8px"
    backgroundColor: --color-accent-light
  warning:
    color: "#f97316"
    borderRadius: "8px"
    backgroundColor: --color-warning-light
  purple:
    color: "#8b5cf6"
    borderRadius: "8px"
    backgroundColor: --color-purple-light
  green:
    color: "#16a249"
    borderRadius: "8px"
    backgroundColor: --color-green-light
  error:
    color: "#ef4444"
    borderRadius: "8px"
    backgroundColor: --color-error-light
  innerYellow:
    padding: "0px"
    backgroundColor: transparent
    color: "#fbbf24"
  innerOrange:
    padding: "0px"
    backgroundColor: transparent
    color: "#fb923c"
  innerBlue:
    padding: "0px"
    backgroundColor: transparent
    color: "#60a5fa"
  innerRed:
    padding: "0px"
    backgroundColor: transparent
    color: "#f87171"
  innerGreen:
    padding: "0px"
    backgroundColor: transparent
    color: "#4ade80"
  innerPurple:
    padding: "0px"
    backgroundColor: transparent
    color: "#a78bfa"
:::

::: page-section {"className": "theme-spacing-hero theme-gradient-primary-to-accent"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "alignItems": "center"}
    ::: page-text {"className": "theme-margin-bottom-2 theme-text-white", "textAlign": "center"}
    # Elevating Your Security Offerings with Verifiable Trust
    :::
    ::: page-text {"textAlign":"center", "className": "theme-margin-bottom-3 theme-text-light-blue theme-text-2xl theme-container-3xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
    TrustRoot offers cybersecurity firms a unique opportunity to lead in the emerging AI security market by providing the foundational protocol for verifiable AI Agent and service authenticity, enabling them to offer critical auditing services and meet enterprise demand for trusted autonomous interactions. This partnership positions firms at the forefront of securing the future's digital landscape.
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Request Partnership Briefing
        icon: Mail
        variant: foreground
        rightIcon: ArrowRight
        url: /contact
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-1"}
    ### Integration & Partnership Models
    :::
    ::: page-block {"className": "theme-container-3xl theme-margin-bottom-1", "align": "center"}
      ::: page-text {"textAlign": "center", "className": "theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
      Expanding Your Capabilities with TrustRoot
      :::
    :::
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-4 theme-text-lg-secondary theme-container-4xl","mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-sm"}}}]}
    At TrustRoot, we believe in empowering cybersecurity firms, not replacing them. Our technology is designed to seamlessly integrate with and amplify your existing security offerings, allowing you to provide a new generation of verifiable trust to your clients. We offer flexible partnership models tailored to accelerate your growth and leadership in the evolving security landscape.
    :::
  :::

  ::: page-block {"className": "theme-container-7xl", "align": "center"}
    ::: page-block {"className": "theme-spacing-xl theme-card-gradient-bg theme-margin-bottom-4", "gap": "2rem", "mediaQueries": [{"maxWidth": "767px", "properties": {"padding": {"top": "1rem", "bottom": "1rem", "left": "1rem", "right": "1rem"}}}]}
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1rem"}
        ::: page-block {"className": "theme-secondary-bg theme-icon-wrapper", "width": "3.25rem", "height": "3.25rem", "border": {"radius": "0.75rem"}}
          ::: page-icon {"name": "Code", "color": "{primary}", "size": "1.5rem"}
          :::
        :::
        ::: page-block {}
          ::: page-text {"className": "theme-text-2xl-white theme-text-bolder"}
          API/SDK Integration Opportunities
          :::
          ::: page-text {"className": "theme-text-white"}
            TrustRoot provides comprehensive APIs (Application Programming Interfaces) and SDKs (Software Development Kits) that enable deep, programmatic integration into your existing security products and services.
          :::
        :::
      :::
      ::: page-feature-grid {"columnsPerRow": 2, "preset": "--component-feature-oneLine"}
        ::: feature
          icon: {"name": "Zap", "size": "var(--font-size-2xl)", "variant": "innerYellow"}
          title: Automated Attestation & Verification
          description: Integrate TrustRoot's attestation engine directly into your clients' CI/CD pipelines to automatically generate and register cryptographic hashes of their applications' frontend code, backend services, or AI agents upon deployment. This allows for continuous, automated integrity checks.
        :::
        ::: feature
          icon: {"name": "Eye", "size": "var(--font-size-2xl)", "variant": "innerRed"}
          title: Real-time Threat Detection
          description: Embed TrustRoot's verification capabilities into your Managed Detection and Response (MDR) platforms, Security Information and Event Management (SIEM) systems, or Extended Detection and Response (XDR) solutions. Receive real-time alerts when a client's attested application or agent deviates from its verified state.
        :::
        ::: feature
          icon: {"name": "FileText", "size": "var(--font-size-2xl)", "variant": "innerGreen"}
          title: Enhanced Reporting & Forensics
          description: Utilize TrustRoot's data feeds to enrich your threat intelligence platforms and forensic tools. Provide your clients with verifiable proof of application integrity before, during, and after incidents, improving root cause analysis and compliance reporting.
        :::
        ::: feature
          icon: {"name": "Settings", "size": "var(--font-size-2xl)", "variant": "innerPurple"}
          title: Custom Solution Development
          description: Leverage TrustRoot's SDKs to build bespoke verifiable security modules or features within your proprietary platforms, allowing for highly customized offerings that meet specific client needs for high-assurance environments.
        :::
      :::
    :::
  :::

  ::: page-block {"className": "theme-container-7xl", "align": "center"}
    ::: page-block {"className": "theme-spacing-xl theme-card-accent-gradient-bg theme-margin-bottom-4", "gap": "2rem", "mediaQueries": [{"maxWidth": "767px", "properties": {"padding": {"top": "1rem", "bottom": "1rem", "left": "1rem", "right": "1rem"}}}]}
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1rem"}
        ::: page-block {"className": "theme-secondary-bg theme-icon-wrapper", "width": "3.25rem", "height": "3.25rem", "border": {"radius": "0.75rem"}}
          ::: page-icon {"name": "TrendingUp", "color": "{accent}", "size": "1.5rem"}
          :::
        :::
        ::: page-block {}
          ::: page-text {"className": "theme-text-2xl-white theme-text-bolder"}
          Joint Go-to-Market Strategies
          :::
          ::: page-text {"className": "theme-text-white"}
            We are committed to collaborative success. TrustRoot seeks strategic partnerships to jointly address the growing demand for verifiable security.
          :::
        :::
      :::
      ::: page-feature-grid {"columnsPerRow": 2, "preset": "--component-feature-oneLine"}
        ::: feature
          icon: {"name": "Award", "size": "var(--font-size-2xl)", "variant": "innerYellow"}
          title: Co-Branded Solutions
          description: Develop joint solutions that combine your existing strengths with TrustRoot's unique verifiable trust capabilities, offering a more robust and differentiated product to the market under a co-branded umbrella.
        :::
        ::: feature
          icon: {"name": "Users", "size": "var(--font-size-2xl)", "variant": "innerBlue"}
          title: Sales Enablement & Training
          description: We provide comprehensive training, sales playbooks, and technical documentation to equip your sales and engineering teams with the knowledge and tools needed to effectively position and implement TrustRoot-enhanced solutions.
        :::
        ::: feature
          icon: {"name": "Target", "size": "var(--font-size-2xl)", "variant": "innerGreen"}
          title: Joint Marketing & Demand Generation
          description: Engage in co-marketing activities, including webinars, whitepapers, case studies, and industry events, to educate the market on the critical need for verifiable trust and showcase the power of our combined offerings.
        :::
        ::: feature
          icon: {"name": "Briefcase", "size": "var(--font-size-2xl)", "variant": "innerOrange"}
          title: Referral & Reseller Programs
          description: Explore structured programs where your firm can act as a trusted advisor, reselling or referring TrustRoot's services to your client base, unlocking new revenue streams and deepening client relationships.
        :::
      :::
    :::
  :::

  ::: page-block {"className": "theme-container-7xl", "align": "center"}
    ::: page-block {"className": "theme-spacing-xl theme-card-purple-gradient-bg theme-margin-bottom-4", "gap": "2rem", "mediaQueries": [{"maxWidth": "767px", "properties": {"padding": {"top": "1rem", "bottom": "1rem", "left": "1rem", "right": "1rem"}}}]}
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1rem"}
        ::: page-block {"className": "theme-secondary-bg", "justifyContent": "center", "alignItems": "center", "stack": {"shrink": "0"}, "width": "3.25rem", "height": "3.25rem", "border": {"radius": "0.75rem"}}
          ::: page-icon {"name": "CheckCircle", "color": "{purple}", "size": "1.5rem"}
          :::
        :::
        ::: page-block {}
          ::: page-text {"className": "theme-text-2xl-white theme-text-bolder"}
          Be Part of TrustRoot's Audit Pool
          :::
          ::: page-text {"className": "theme-text-white"}
            As pioneers in verifiable trust, we recognize the critical role of independent verification. Cybersecurity firms can join a specialized "Audit Pool" to provide third-party validation and auditing services for applications, agents, and TEEs attested on the TrustRoot network.
          :::
        :::
      :::
      ::: page-feature-grid {"columnsPerRow": 3, "preset": "--component-feature-oneLine"}
        ::: feature
          icon: {"name": "ArrowRight", "size": "var(--font-size-2xl)", "variant": "innerGreen"}
          title: Expanding Service Offerings
          description: This enables your firm to develop new revenue streams by offering specialized "TrustRoot Compliance" or "Verifiable Integrity Audit" services to organizations leveraging TrustRoot.
        :::
        ::: feature
          icon: {"name": "Award", "size": "var(--font-size-2xl)", "variant": "innerBlue"}
          title: Industry Leadership
          description: Position your firm at the forefront of the verifiable security movement, becoming an essential trusted party in the ecosystem validating the integrity of AI, dApps, and critical online services.
        :::
        ::: feature
          icon: {"name": "Zap", "size": "var(--font-size-2xl)", "variant": "innerYellow"}
          title: Access to Cutting-Edge Technology
          description: Gain early access and deep understanding of TrustRoot's evolving technology stack, allowing your experts to shape the future of verifiable security.
        :::
      :::
    :::
  :::

  ::: page-block {"className": "theme-container-7xl", "align": "center"}
    ::: page-block {"className": "theme-spacing-xl theme-card-warning-gradient-bg", "gap": "2rem", "mediaQueries": [{"maxWidth": "767px", "properties": {"padding": {"top": "1rem", "bottom": "1rem", "left": "1rem", "right": "1rem"}}}]}
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "1rem"}
        ::: page-block {"className": "theme-secondary-bg theme-icon-wrapper", "width": "3.25rem", "height": "3.25rem", "border": {"radius": "0.75rem"}}
          ::: page-icon {"name": "Handshake", "color": "{warning}", "size": "1.5rem"}
          :::
        :::
        ::: page-block {}
          ::: page-text {"className": "theme-text-2xl-white theme-text-bolder"}
          Partnership Opportunities
          :::
          ::: page-text {"className": "theme-text-white"}
            Beyond specific integration and audit roles, TrustRoot is open to broader strategic alliances. We welcome discussions on:
          :::
        :::
      :::
      ::: page-feature-grid {"columnsPerRow": 3, "preset": "--component-feature-oneLine"}
        ::: feature
          icon: {"name": "Settings", "size": "var(--font-size-2xl)", "variant": "innerBlue"}
          title: Technology Alliances
          description: Collaborating on research, development, and interoperability standards for verifiable computation and trusted execution environments.
        :::
        ::: feature
          icon: {"name": "Shield", "size": "var(--font-size-2xl)", "variant": "innerGreen"}
          title: Managed Security Service Provider (MSSP) Partnerships
          description: Integrating TrustRoot into your managed security services to offer clients continuous, proactive monitoring and alerting for application and agent integrity.
        :::
        ::: feature
          icon: {"name": "Users", "size": "var(--font-size-2xl)", "variant": "innerPurple"}
          title: Advisory Roles
          description: Engaging your firm's expertise in shaping TrustRoot's product roadmap and compliance strategies.
        :::
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg", "padding": {"left": "1rem", "right": "1rem", "bottom": "5rem"}}
  ::: page-block {"className": "theme-container-4xl", "align": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-1"}
    ### Use Cases: How TrustRoot Enhances Your Security Portfolio
    :::
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-4 theme-text-lg-secondary theme-container-4xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    TrustRoot doesn't just add a new layer of security; it fundamentally enhances and expands the capabilities of your existing cybersecurity products, allowing you to protect against threats that traditional solutions often miss.
    :::
  :::

  ::: page-block {"className": "theme-container-7xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 2, "isOneLine": "true", "textAlign": "left", "description": {"font": {"size": "var(--font-size-md)"}}}
      ::: feature
        icon: {"name": "Globe", "size": "32px", "variant": "primary"}
        title: Complementing Web Application Firewalls (WAFs)
        description: While WAFs protect against malicious traffic entering the application, they typically don't verify the integrity of the code that actually loads and executes in the user's browser. TrustRoot provides this critical missing link, ensuring that even legitimate traffic isn't delivering tampered frontend code due to a supply chain attack (e.g., compromised third-party JavaScript libraries). Your WAF stops the attack at the perimeter; TrustRoot verifies the integrity of what's running within the browser.
      :::
      ::: feature
        icon: {"name": "Lock", "size": "32px", "variant": "accent"}
        title: Strengthening Cloud Security Posture Management (CSPM) and Cloud Workload Protection Platforms (CWPP)
        description: TrustRoot extends cloud security beyond infrastructure and configuration. By attesting to the integrity of serverless functions, container images, and microservices running within Trusted Execution Environments, TrustRoot ensures that even within highly elastic cloud environments, the application logic itself remains uncompromised and verifiably authentic, protecting against insider threats or sophisticated runtime attacks.
      :::
      ::: feature
        icon: {"name": "Code", "size": "32px", "variant": "purple"}
        title: Providing New Application Security (AppSec) Capabilities
        description: Traditional AppSec often focuses on static/dynamic analysis (SAST/DAST) and runtime application self-protection (RASP). TrustRoot introduces verifiable runtime integrity. This means your clients can continuously verify that their deployed applications haven't been maliciously altered post-deployment. This offers a powerful new capability for detecting sophisticated persistent threats, supply chain compromises, and unauthorized code injections that bypass typical AppSec scans.
      :::
      ::: feature
        icon: {"name": "Brain", "size": "32px", "variant": "green"}
        title: Enhancing AI Security and Governance
        description: As AI agents become mission-critical, their trustworthiness is paramount. TrustRoot allows your clients to prove the authenticity of their AI models and execution paths. This enables your firm to offer new services for AI governance, compliance, and risk management, assuring clients that their AI agents are behaving predictably and securely, from model training to inference.
      :::
      ::: feature
        icon: {"name": "AlertTriangle", "size": "32px", "variant": "warning"}
        title: Robust Supply Chain Security
        description: For firms dealing with software supply chain risks (e.g., SBOMs, vulnerability management), TrustRoot offers a direct mechanism to cryptographically link deployed code to its original, attested source. This provides an immutable chain of trust that helps detect and mitigate tampering at any stage of the software delivery pipeline, significantly bolstering existing supply chain security offerings.
      :::
    :::
  :::
:::

::: page-section {"className": "theme-gradient-primary-to-accent"}
  ::: page-block {"align": "center", "textAlign": "center", "className": "theme-container-4xl", "gap": "1.5rem"}
    ::: page-text {"className": "theme-text-white", "textAlign": "center"}
    ### Ready to Partner with TrustRoot?
    :::
    ::: page-text {"textAlign":"center", "className": "theme-margin-bottom-1 theme-text-light-blue theme-text-xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Let's discuss how we can work together to define the future of digital trust
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Contact Business Development
        icon: Mail
        variant: foreground
        url: /contact
      :::
    :::
  :::
::: 