---
# GENERAL
theme: default
author: Thomas PIERRE for StudioB04
titleTemplate: '%s | StudioB04'
title: StudioB04
keywords: Formation, Svelte, Web, Javascript
favicon: favicon.png
colorSchema: light
contextMenu: false
htmlAttrs:
  dir: ltr  
  lang: fr

# STYLE
fonts:
  sans: Red Hat Display
  serif: Robot Slab
  mono: monospace
themeConfig:
  primary: var(--primary-500)
  secondary: var(--secondary-500)

# CONFIG
presenter: true
lineNumbers: true
monaco: true
monacoTypesSource: local
selectable: true
drawings:
  enabled: true
  persist: false
  presenterOnly: true
  syncAll: true
mdc: true

layout: cover # https://sli.dev/builtin/layouts
transition: fade-out
src: ./slides/accueil.html
---

--- 
title: Programme
src: ./slides/programme.html
---


--- 
title: Introduction
src: ./slides/1.presentation.html
---


--- 
title: Installation
src: ./slides/2.installation.html
---


--- 
title: Organisation
src: ./slides/3.organisation.html
---


--- 
title: Organisation
src: ./slides/4.routes.html
---

--- 
title: Layouts
src: ./slides/5.layouts.html
---

--- 
title: Deploiement
src: ./slides/6.deploiement.html
---
