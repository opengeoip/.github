# .github

The public profile of the [opengeoip](https://github.com/opengeoip) organisation.

| Path | Content |
|---|---|
| `profile/README.md` | the page shown on the organisation home |
| `brand` | the logo and the banner, as SVG sources and PNG renderings |

The PNG files are rendered from the SVG sources with `rsvg-convert` (package `librsvg2-bin`):

```sh
rsvg-convert -w 512 -h 512 brand/logo.svg -o brand/logo.png
rsvg-convert -w 1280 -h 640 brand/banner.svg -o brand/banner.png
```
