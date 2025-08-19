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

  ::: page-block {"className": "theme-container-5xl theme-border theme-background-bg theme-box-shadow-xl theme-border-radius-2xl", "align": "center", "gap": "2rem", "padding": {"top": "2rem", "bottom": "1rem"}}
    ::: page-text {"className": "theme-text-bolder", "padding": {"left": "2rem", "right": "2rem"}}
    #### Update Trading Agent
    :::

    ::: page-protected-content {"showLoginMessage": true}
      ::: agent-settings
      :::
    :::
  :::
:::