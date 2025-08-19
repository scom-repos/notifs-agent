::: var
primary: "var(--color-primary-main)"
secondary: "var(--color-text-secondary)"
:::

::: fetch-data
endpoint: {global.env.BASE_URL}blog-posts/:id.json
method: GET
headers:
  Authorization: "Bearer {env.API_TOKEN}"
as: "record"
:::

::: page-section {"className": "theme-secondary-bg"}
  ::: page-block {"className": "theme-container-5xl theme-margin-bottom-2", "align": "center"}
    ::: page-link {"url": "/blog", "textDecoration": "none"}
      ::: page-icon {"name": "ArrowLeft", "size": "1rem", "color": "{primary}"}
      :::
      ::: page-text {"font": {"color": "{primary}", "weight": 500}, "lineHeight": 1}
      Back to Blog
      :::
    :::
  :::

  ::: page-block {"className": "theme-container-5xl theme-spacing-lg theme-border theme-background-bg theme-box-shadow-xl theme-border-radius-2xl", "align": "center", "gap": "1rem"}
    ::: page-text {"className": "theme-text-bolder"}
    ### {record.title}
    :::

    ::: page-stack {"gap": "1rem", "direction": "horizontal", "alignItems": "center"}
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "0.5rem"}
        ::: page-icon {"name": "Calendar", "size": "1rem", "color": "{secondary}"}
        :::
        ::: page-text {"className": "theme-text-sm-secondary"}
          ::expression[new Date(record.date).toLocaleDateString()]
        :::
      :::
      ::: page-stack {"direction": "horizontal", "alignItems": "center", "gap": "0.5rem"}
        ::: page-icon {"name": "User", "size": "1rem", "color": "{secondary}"}
        :::
        ::: page-text {"className": "theme-text-sm-secondary"}
        {record.author}
        :::
      :::
    :::
    ::: page-block {"margin": {"top": "0.5rem", "bottom": "1rem"}}
      ::: page-text {}
        {record.content}
      :::
    :::
  :::
::: 