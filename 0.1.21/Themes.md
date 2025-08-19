# Themes Configuration

This file defines the available themes for the application. Each theme is defined as a block with its configuration.

::: base
borderRadius:
  sm: "4px"
  md: "6px"
  lg: "8px"
  xl: "12px"
  2xl: "16px"
  3xl: "24px"

spacing:
  xs: "0.25rem"
  sm: "0.5rem"
  md: "1rem"
  lg: "2rem"
  xl: "3rem"
  section: "5rem 3rem"
  block: "1.5rem"
  gap: "1rem"
  margin: "1rem"
  padding: "1rem"

font:
  body: "system-ui, sans-serif"
  heading: "inherit"
  weight: "400"
  lineHeight: "1.5"
  textAlign: "left"
  size:
    xs: "0.75rem"
    sm: "0.875rem"
    md: "1rem"
    lg: "1.125rem"
    xl: "1.25rem"
    2xl: "1.5rem"
    3xl: "1.875rem"
    4xl: "2.25rem"
    5xl: "3rem"
    6xl: "3.75rem"

border:
  width: "1px"
  style: "solid"

container:
  maxWidth: "72rem"
  7xl: "80rem"
  6xl: "72rem"
  5xl: "64rem"
  4xl: "56rem"
  3xl: "48rem"
  2xl: "40rem"
  xl: "36rem"
  lg: "32rem"
  md: "28rem"
  sm: "24rem"
  xs: "20rem"

shadow:
  sm: "0 1px 2px 0 rgb(0 0 0 / 0.05)"
  md: "0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1)"
  lg: "0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1)"
  xl: "0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1)"
  2xl: "0 25px 50px -12px rgb(0 0 0 / 0.25)"
  inner: "inset 0 2px 4px 0 rgb(0 0 0 / 0.05)"
  none: "0 0 #0000"
component:
  card:
    default: "{"background": {"color": "var(--color-secondary)"}, "padding": {"top": "var(--spacing-lg)", "bottom": "var(--spacing-lg)", "left": "var(--spacing-lg)", "right": "var(--spacing-lg)"}, "border": {"radius": "var(--borderRadius-2xl)"}, "align": "center"}"
    gradientPrimary: "{"background": {"image": "var(--color-gradient-primary)"}, "padding": {"top": "var(--spacing-lg)", "left": "var(--spacing-lg)", "right": "var(--spacing-lg)", "bottom": "var(--spacing-lg)"}, "border": {"radius": "var(--borderRadius-lg)", "width": "1px", "style": "solid", "color": "var(--color-primary-main)"}}"
    gradientAccent: "{"background": {"image": "var(--color-gradient-success)"}, "padding": {"top": "var(--spacing-lg)", "left": "var(--spacing-lg)", "right": "var(--spacing-lg)", "bottom": "var(--spacing-lg)"}, "border": {"radius": "var(--borderRadius-lg)", "width": "1px", "style": "solid", "color": "var(--color-accent-main)"}}"
  feature:
    noBorder: "{"border": {"radius": "var(--borderRadius-lg)", "width": "1px", "style": "solid", "color": "var(--color-border)"}, "columnsPerRow": 2, "gap": "0px", "isArrowShown": true, "item": {"background": {"color": "transparent"}, "border": {"style": "none"}, "boxShadow": "none", "hover": {"transform": "translateY(0px)"}}}"
    oneLine: "{"item": {"background": {"color": "#1e293b99"}, "border": {"color": "#33415580"}}, "isOneLine": true, "title": {"font": {"size": "var(--font-size-lg)", "color": "#fff"}}, "description": {"font": {"color": "#cbd5e1"}}}"
  badge:
    default: "{"border": {"radius": "999px"}, "padding": {"top": "0.125rem", "bottom": "0.125rem", "left": "0.625rem", "right": "0.625rem"}, "width": "max-content", "direction": "horizontal", "gap": "0.5rem", "alignItems": "center", "justifyContent": "center"}"
:::

::: theme {"name": "light", "default": true}
color:
  background: "#fff"
  foreground: "#222"
  secondary: "#f1f5f9"
  border: "hsl(214.3 31.8% 91.4%)"
  primary:
    main: "#2563eb"
    light: "#2466eb33"
    dark: "#1e40af"
  accent:
    main: "#0d968b"
    light: "#0d968b33"
  purple:
    main: "#9234ea"
    light: "#8b5cf633"
  green:
    main: "#16a249"
    light: "#16a24933"
  error:
    main: "#ef4444"
    light: "#ef444433"
  warning:
    main: "#f97316"
    light: "#f9731633"
  tertiary: "#e5e7eb"
  button:
    bg: "#2563eb"
    fg: "#fff"
    hoverBg: "#1d4ed8"
    hoverFg: "#fff"
  text:
    primary: "#020817"
    secondary: "hsl(215 16% 35%)"
  gradient:
    primary: "linear-gradient(135deg, #eff6ff 0%, #e0e7ff 100%)"
    home: "linear-gradient(to bottom right, #effbff, #ffffff, #e6fffa)"
    success: "linear-gradient(135deg, #ecfdf5 0%, #f0fdf4 100%)"
    warning: "linear-gradient(135deg, #fef3c7 0%, #feebc8 100%)"
    purple: "linear-gradient(135deg, #faf5ff 0%, #ede9fe 100%)"
    error: "linear-gradient(135deg, #fef2f2 0%, #fee2e2 100%)"

font:
  color: "#020817"

border:
  radius: "8px"
  color: "#e2e8f0"
:::

::: theme {"name": "dark"}
color:
  background: "#020817"
  foreground: "#fff"
  secondary: "#1e293b80"
  border: "hsl(217.2 32.6% 17.5%)"
  primary:
    main: "#2563eb"
    light: "#2466eb33"
    dark: "#1e40af"
  accent:
    main: "#0d968b"
    light: "#0d968b33"
  purple:
    main: "#9234ea"
    light: "#8b5cf633"
  green:
    main: "#4ade80"
    light: "#16a24933"
  error:
    main: "#ef4444"
    light: "#ef444433"
  warning:
    main: "#f97316"
    light: "#f9731633"
  tertiary: "#1e2e52"
  button:
    bg: "#2563eb"
    fg: "#fff"
    hoverBg: "#1d4ed8"
    hoverFg: "#fff"
  text:
    primary: "#fff"
    secondary: "#94a3b8"
  gradient:
    primary: "linear-gradient(135deg, #a0c6ff1a 0%, #a0c6ff12 100%)"
    home: "linear-gradient(to bottom right, #111827, #1f2937, #111827)"
    success: "linear-gradient(135deg, #0596690f 0%, #05966912 100%)"
    warning: "linear-gradient(135deg, #ffe5661a 0%, #ffe56600 100%)"
    purple: "linear-gradient(135deg, #c084fc1a 0%, #c084fc1a 100%)"
    error: "linear-gradient(135deg, #fee2e21a 0%, #fee2e212 100%)"

font:
  color: "#fff"

border:
  radius: "8px"
  color: "hsl(217.2 32.6% 17.5%)"
:::

::: theme {"name": "ocean"}
color:
  background: "#f0f9ff"
  foreground: "#0f172a"
  secondary: "#e0f2fe"
  border: "#bae6fd"
  primary:
    main: "#0284c7"
    light: "#0284c733"
    dark: "#004b8d"
  accent:
    main: "#0891b2"
    light: "#0891b233"
  purple:
    main: "#7c3aed"
    light: "#7c3aed33"
  green:
    main: "#059669"
    light: "#05966933"
  error:
    main: "#dc2626"
    light: "#dc262633"
  warning:
    main: "#ea580c"
    light: "#ea580c33"
  tertiary: "#e0f2fe"
  button:
    bg: "#0284c7"
    fg: "#fff"
    hoverBg: "#0369a1"
    hoverFg: "#fff"
  text:
    primary: "#0f172a"
    secondary: "#64748b"
  gradient:
    primary: "linear-gradient(135deg, #e0f2fe 0%, #bae6fd 100%)"

font:
  color: "#0f172a"

border:
  radius: "10px"
  color: "#bae6fd"

shadow:
  sm: "0 1px 3px 0 rgb(59 130 246 / 0.1)"
  md: "0 4px 6px -1px rgb(59 130 246 / 0.15), 0 2px 4px -2px rgb(59 130 246 / 0.1)"
  lg: "0 10px 15px -3px rgb(59 130 246 / 0.15), 0 4px 6px -4px rgb(59 130 246 / 0.1)"
  xl: "0 20px 25px -5px rgb(59 130 246 / 0.15), 0 8px 10px -6px rgb(59 130 246 / 0.1)"
  2xl: "0 25px 50px -12px rgb(59 130 246 / 0.25)"
  inner: "inset 0 2px 4px 0 rgb(59 130 246 / 0.05)"
  none: "0 0 #0000"
:::

::: theme {"name": "sunset"}
color:
  background: "#fef3e2"
  foreground: "#1c1917"
  secondary: "#fed7aa"
  border: "#fdba74"
  primary:
    main: "#ea580c"
    light: "#ea580c33"
    dark: "#d97706"
  accent:
    main: "#dc2626"
    light: "#dc262633"
  purple:
    main: "#c2410c"
    light: "#c2410c33"
  green:
    main: "#16a34a"
    light: "#16a34a33"
  error:
    main: "#dc2626"
    light: "#dc262633"
  warning:
    main: "#d97706"
    light: "#d9770633"
  tertiary: "#1c1917"
  button:
    bg: "#ea580c"
    fg: "#fff"
    hoverBg: "#dc2626"
    hoverFg: "#fff"
  text:
    primary: "#1c1917"
    secondary: "#78716c"
  gradient:
    primary: "linear-gradient(135deg, #fef3e2 0%, #fed7aa 100%)"

font:
  color: "#1c1917"

border:
  radius: "12px"
  color: "#fdba74"

shadow:
  sm: "0 1px 3px 0 rgb(234 88 12 / 0.1)"
  md: "0 4px 6px -1px rgb(234 88 12 / 0.15), 0 2px 4px -2px rgb(234 88 12 / 0.1)"
  lg: "0 10px 15px -3px rgb(234 88 12 / 0.15), 0 4px 6px -4px rgb(234 88 12 / 0.1)"
  xl: "0 20px 25px -5px rgb(234 88 12 / 0.15), 0 8px 10px -6px rgb(234 88 12 / 0.1)"
  2xl: "0 25px 50px -12px rgb(234 88 12 / 0.25)"
  inner: "inset 0 2px 4px 0 rgb(234 88 12 / 0.05)"
  none: "0 0 #0000"
:::
