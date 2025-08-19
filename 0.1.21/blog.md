::: var
buttonVariants:
  foreground:
    backgroundColor: "#fff"
    color: "#2563eb"
    border: "1px solid #2563eb"
    borderRadius: "8px"
    padding: "0.5rem 1rem"
    fontSize: "1rem"
    fontWeight: 600
  outline:
    backgroundColor: "transparent"
    color: "#fff"
    border: "1px solid --color-border"
    borderRadius: "8px"
    padding: "0.5rem 1rem"
    fontSize: "1rem"
    fontWeight: 600
  primary:
    backgroundColor: "#2563eb"
    color: "#fff"
    border: "1px solid #2563eb"
    borderRadius: "8px"
    padding: "0.5rem 1rem"
    fontSize: "1rem"
    fontWeight: 600
:::

::: page-section {"className": "theme-spacing-hero theme-gradient-bottom-right-dark"}
  ::: page-block {"className": "theme-container-4xl theme-margin-bottom-4", "align": "center", "gap": "1.5rem", "alignItems": "center"}
    ::: page-text {"textAlign": "center", "className": "theme-text-white"}
    # TrustRoot ::gradient[Blog & News]{className: theme-gradient-accent-to-primary-text}
    :::
    ::: page-text {"textAlign":"center", "className": "theme-container-3xl theme-text-light-gray theme-text-2xl", "mediaQueries": [{"maxWidth": "767px", "properties": {"font": {"size": "--font-size-lg"}}}]}
    Stay updated with the latest developments in digital trust, security protocols, autonomous agent technology, and industry insights from our expert team.
    :::
  :::
:::

::: page-section {"padding": {"top": "3rem", "bottom": "0px", "left": 0, "right": 0}, "className": "theme-background-bg"}
  ::: page-blog-list {"latest": {"columnsPerRow": 3, "showLinks": true, "maxWidth": "--container-6xl"}, "featured": {"columnsPerRow": 1, "showLinks": true, "direction": "row", "title": {"font": {"size": "var(--font-size-3xl)"}}, "excerpt": {"font": {"size": "var(--font-size-lg)"}}, "image": {"width": "100%", "height": "100%"}, "content": {"padding": "{spacing.blog}"}, "link": {"font": {"size": "var(--font-size-md)"}}, "maxWidth": "--container-6xl"}}
    ::: filter
      id: all
      label: All Posts
      icon: Globe
    :::
    ::: filter
      id: security
      label: Security
      icon: Shield
    :::
    ::: filter
      id: technology
      label: Technology
      icon: Code
    :::
    ::: filter
      id: ai-agents
      label: AI Agents
      icon: Bot
    :::
    ::: filter
      id: industry-news
      label: Industry News
      icon: TrendingUp
    :::
    ::: fetch-data
      endpoint: {global.env.BASE_URL}blog-posts/posts.json
      method: GET
      as: posts
    :::
  :::
:::
