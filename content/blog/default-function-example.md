---
title: "Default Function Example"
date: 2021-10-02T14:38:57-03:00
draft: true
font:
oldparam: The default function helps make your templating DRYer.
newparam:
---

{{ index .Params "font" | default "Roboto" }}
{{ default "Roboto" (index .Params "font") }}
