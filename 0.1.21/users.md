::: var
primary: var(--color-primary-main)
accent: var(--color-accent-main)
warning: var(--color-warning-main)
error: var(--color-error-main)
purple: var(--color-purple-main)
green: var(--color-green-main)
secondary: var(--color-secondary)
textSecondary: var(--color-text-secondary)
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
featureVariants:
  primary:
    backgroundColor: "#3b82f61a"
  green:
    backgroundColor: "#16a2491a"
  warning:
    backgroundColor: "#e9590c1a"
  purple:
    backgroundColor: "#9234ea1a"
  gradientGreen:
    backgroundColor: --color-gradient-success
    borderColor: "#bbf7d0"
    borderWidth: "2px"
  gradientWarning:
    backgroundColor: --color-gradient-warning
    borderColor: "#fef08a"
    borderWidth: "2px"
  gradientError:
    backgroundColor: --color-gradient-error
    borderColor: "#fecaca"
    borderWidth: "2px"
iconVariants:
  primary:
    backgroundColor: "#2466eb33"
    color: "#2563eb"
  accent:
    backgroundColor: "#0d968b33"
    color: "#0d968b"
  warning:
    backgroundColor: "#f9731633"
    color: "#f97316"
  purple:
    backgroundColor: "#8b5cf633"
    color: "#8b5cf6"
  green:
    backgroundColor: "#16a24933"
    color: "#16a249"
  error:
    backgroundColor: "#ef444433"
    color: "#ef4444"
:::

::: page-section {"className": "theme-gradient-primary-to-accent theme-spacing-hero"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "alignItems": "center", "gap": "1.5rem"}
    ::: page-text {"className": "theme-text-white", "textAlign": "center"}
    # Your Digital Shield: How TrustRoot Protects Your ::gradient[Online Interactions]{className: theme-text-light-green}
    :::
    ::: page-text {"className": "theme-text-lg-bold theme-text-light-green", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Are you sure that DApp isn't a fake? Is your money truly safe from phishing?
    :::
    ::: page-text {"className": "theme-text-lg theme-text-light-green theme-margin-bottom-2 theme-container-3xl", "textAlign":"center", "opacity": 0.9, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    It's tough to know if a website or DApp is real because attackers create perfect fake sites and inject malicious code directly into the software supply chain of legitimate services. This bypasses traditional defenses. With AI agents now mimicking real entities, verifying digital authenticity is becoming even more complex and critical.
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Download TrustRoot Extension
        icon: Download
        variant: accent
        url: https://chrome.google.com/webstore/detail/trustroot
      :::
      ::: button
        caption: Learn More in FAQ
        icon: Book
        variant: foreground
        url: faq
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### How TrustRoot Helps YOU
    :::
    ::: page-text {"textAlign": "center", "className": "theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Comprehensive protection for your digital interactions
    :::
  :::
    
  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 2, "textAlign": "left"}
      ::: feature
        icon: {"name": "Shield", "variant": "primary"}
        title: Protects you from fake websites and phishing scams
        description: TrustRoot automatically checks if websites and apps are genuine before you interact with them, warning you immediately if something seems off.
        variant: primary
      :::
      
      ::: feature
        icon: {"name": "CheckCircle", "variant": "green"}
        title: Ensures the apps you use haven't been tampered with
        description: By verifying the integrity of applications and services, TrustRoot makes sure you're using the real, unmodified version that the developers intended.
        variant: green
      :::
      
      ::: feature
        icon: {"name": "Bot", "variant": "purple"}
        title: Helps ensure that autonomous agents acting on your behalf are legitimate
        description: As AI agents become more common, TrustRoot will help verify that these smart programs are authentic and haven't been compromised or impersonated.
        variant: purple
      :::
      
      ::: feature
        icon: {"name": "HelpCircle", "variant": "warning"}
        title: Provides transparency through the TrustRoot Explorer
        description: Even without our browser extension, you can check the TrustRoot Explorer website to see if any registered service has been compromised.
        variant: warning
      :::
    :::
  :::
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### How Can I Use TrustRoot?
    :::
    ::: page-text {"textAlign": "center", "className": "theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Multiple ways to protect yourself and verify authenticity
    :::
  :::
    
  ::: page-block {"className": "theme-container-6xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 3, "textAlign": "center"}
      ::: feature
        icon: {"name": "Download", "variant": "primary"}
        title: Chrome Extension
        description: Install our browser extension to automatically verify websites and DApps as you browse.
        link: { "caption": "Install Extension", "url": "https://chrome.google.com/webstore/detail/trustroot" }
      :::
      
      ::: feature
        icon: {"name": "Shield", "variant": "green"}
        title: Mobile App Launcher
        description: Use our mobile app to safely launch and verify DApps and other applications on your phone.
        link: { "caption": "Download App", "url": "https://play.google.com/store/apps/details?id=com.trustroot.trustroot" }
      :::
      
      ::: feature
        icon: {"name": "HelpCircle", "variant": "purple"}
        title: TrustRoot Explorer
        description: Visit our public explorer to check the verification status of any registered service or application.
        link: { "caption": "Visit Explorer", "url": "https://trustroot.org/explorer" }
      :::
    :::
  :::
:::

::: page-section {"className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "gap": "var(--spacing-gap)"}
    ::: page-text {"textAlign": "center"}
    ### What to Look For
    :::
    ::: page-text {"textAlign": "center", "className": "theme-text-xl-secondary", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Know exactly when you're protected and what to do if something's wrong
    :::
  :::
    
  ::: page-block {"className": "theme-container-4xl", "align": "center"}
    ::: page-feature-grid {"columnsPerRow": 3, "textAlign": "center", "description": {"className": "theme-text-md"}}
      ::: feature
        icon: {"name": "CheckCircle", "variant": "green"}
        title: Verified & Safe
        description: Green TrustRoot badge means the site or app is verified and safe to use
        variant: gradientGreen
      :::
      
      ::: feature
        icon: {"name": "AlertTriangle", "variant": "warning"}
        title: Warning: Check Required
        description: Yellow badge means additional verification needed - check TrustRoot Explorer
        variant: gradientWarning
      :::
      
      ::: feature
        icon: {"name": "AlertTriangle", "variant": "error"}
        title: Danger: Not Verified
        description: Red badge indicates the site or app failed verification - do not proceed
        variant: gradientError
      :::
    :::
  :::
:::

::: page-section {"id": "faq", "className": "theme-background-bg"}
  ::: page-block {"className": "theme-container-4xl", "align": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-margin-bottom-4"}
    ### Frequently Asked Questions
    :::
    
    ::: page-block {"gap": "2rem", "className": "theme-container-4xl", "align": "center"}
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-primary-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Shield", "color": "{primary}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
            What is TrustRoot, and how does it protect me online?
            :::
            ::: page-text
            TrustRoot is like a digital guardian that verifies if the websites, apps, and even smart AI programs you interact with are genuine and haven't been secretly tampered with. It protects you from scams like fake websites trying to steal your information, ensuring you're always connecting to the real deal.
            :::
          :::
        :::
      :::

      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-purple-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "HelpCircle", "color": "{purple}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
            Do I need to be a tech expert to use TrustRoot?
            :::
            ::: page-text
            Not at all! TrustRoot is designed to work quietly in the background, often through a simple browser extension or built into apps. You don't need to understand complex code or blockchain — TrustRoot does the heavy lifting to keep you safe.
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-accent-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Globe", "color": "{accent}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
            Is TrustRoot only for crypto or blockchain users (like DApps)?
            :::
            ::: page-text
            While TrustRoot is fantastic for securing DApps, its core technology works for any online service or website, including traditional banking apps, e-commerce sites, and even the future wave of AI-powered services. Our goal is universal digital trust.
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-warning-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "AlertTriangle", "color": "{warning}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
            How can I tell if a website or app is fake or has been hacked?
            :::
            ::: page-text
            It's getting harder to tell on your own because hackers make fakes look identical to real ones. TrustRoot helps by automatically checking if the site or app you're using matches its official, uncompromised version. If something's wrong, TrustRoot will warn you immediately.
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-green-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Lock", "color": "{green}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
            What kind of things does TrustRoot protect me from?
            :::
            ::: page-text
            TrustRoot protects against phishing scams (fake websites), malware injected into legitimate apps, and dangerous 'supply chain attacks' where bad code is slipped into software before it even reaches you. It also prepares for a future where AI agents need to prove they are who they say they are.
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-error-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Shield", "color": "{error}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
            How is TrustRoot different from my antivirus or firewall?
            :::
            ::: page-text
            Your antivirus and firewall are essential for blocking known threats and protecting your device. TrustRoot adds a critical layer by verifying the authenticity and integrity of the digital services themselves. It's like having a system that confirms the person you're talking to is truly who they claim to be, even if they bypassed your front-door security.
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-primary-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Search", "color": "{primary}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
            What if I don't have the TrustRoot browser extension? Can I still check a site's authenticity?
            :::
            ::: page-text
            Yes! Even without the extension, if a website or app is registered with TrustRoot and then gets compromised, we'll list it on our public TrustRoot Explorer website. You can visit the Explorer to independently verify if a site you're curious about is truly safe.
            :::
          :::
        :::
      :::
      
      ::: page-block {"preset": "--component-card-default"}
        ::: page-stack {"direction": "horizontal", "gap": "1rem"}
          ::: page-block {"className": "theme-purple-bg theme-icon-wrapper", "width": "2rem", "height": "2rem"}
            ::: page-icon {"name": "Bot", "color": "{purple}", "size": "1rem"}
            :::
          :::
          ::: page-block {"gap": "1rem"}
            ::: page-text {"className": "theme-text-xl theme-text-bolder", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
            What is an "AI Agent," and how does TrustRoot make them safe?
            :::
            ::: page-text
            AI Agents are smart computer programs that can act on their own, like automated assistants or advanced chatbots. In the future, they'll do more and more for us online. TrustRoot will help ensure that these AI agents are real, trustworthy, and haven't been hijacked or programmed with malicious intent, so you can interact with them safely.
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
    ### Ready to Browse with Complete Confidence?
    :::
    ::: page-text {"className": "theme-text-xl theme-text-light-gray theme-margin-bottom-1", "textAlign":"center", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}}}]}
    Join thousands of users who trust TrustRoot to protect their digital interactions
    :::
    ::: page-button {"align": "center", "font": {"size": "var(--font-size-xl)"}, "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-md"}, "padding": {"left": "1rem", "right": "1rem"}}}]}
      ::: button
        caption: Install TrustRoot Now
        icon: Download
        variant: foreground
        url: https://chrome.google.com/webstore/detail/trustroot
      :::
      ::: button
        caption: Learn More
        variant: outline
        url: /developers
        rightIcon: ArrowRight
      :::
    :::
  :::
::: 