# PaperMod

[stephentuso.com](https://stephentuso.com) fork

View [original repo](https://github.com/adityatelange/hugo-PaperMod) for documentation.

Modifications:
  - "Powered by" message removed
  - Changed nav width to match content width
  - Commments always dark themed
  - Removed highlight JS
  - Made code blocks match theme (light/dark)

In order for code blocks to switch with theme toggle, your `config.yaml` needs:
```yaml
markup:
  highlight:
    noClasses: false
```