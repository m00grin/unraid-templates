# Unraid templates

Unraid [Community Apps](https://ca.unraid.net) templates for [ph-intercept](https://github.com/m00grin/ph-intercept), a real-time DNS dashboard for Pi-hole, AdGuard Home, and Technitium DNS.

| File | What it is |
|------|------------|
| `templates/ph-intercept.xml` | Docker template: image, port, and every setting with a description |
| `ca_profile.xml` | Author profile shown in Community Apps |
| `images/ph-intercept.png` | App icon |

The template pulls `m00grin/ph-intercept:latest` from Docker Hub, the same image published to GHCR.

**Support:** please open issues on the [ph-intercept repository](https://github.com/m00grin/ph-intercept/issues), not here.

## Manual install (before or without Community Apps)

In Unraid, go to **Docker → Add Container**, paste this into **Template**, and fill in your DNS provider's URL and credentials:

```
https://raw.githubusercontent.com/m00grin/unraid-templates/main/templates/ph-intercept.xml
```

The icon is based on the [Lucide](https://lucide.dev) crosshair icon (ISC license).
