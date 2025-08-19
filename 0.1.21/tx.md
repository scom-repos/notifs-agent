::: var
primary: #2563eb
accent: var(--color-accent-main)
secondary: #9ca3af
warning: #b45309
yellow: #eab308
error: #ef4444
primaryBg: #2563eb33
errorBg: #ef444433
yellowBg: #eab30833
warningBg: #b4530933
textSecondary: var(--color-text-secondary)
buttonVariants:
  ghost:
    backgroundColor: "transparent"
    color: "#2563eb"
    border: "none"
    borderRadius: "8px"
    boxShadow: "none !important"
    padding: "0"
    fontSize: "1rem"
    fontWeight: 600
:::

::: fetch-data
endpoint: ''
method: GET
as: "detail"
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-5xl theme-margin-bottom-2", "align": "center"}
    ::: page-link {"url": "/leaderboard", "textDecoration": "none"}
      ::: page-icon {"name": "ArrowLeft", "size": "1rem", "color": "{primary}"}
      :::
      ::: page-text {"font": {"color": "{primary}", "weight": 500}, "lineHeight": 1}
      Back to Leaderboard
      :::
    :::
  :::

  ::: page-block {"className": "theme-container-5xl", "align": "center", "gap": "2rem"}
    ::: page-text {}
    #### Transaction Details
    :::
    ::: trade-detail
    :::
  :::
:::