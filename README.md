# LTV Media PRO — ltvmedia.net

Landing page for [ltvmedia.net](https://ltvmedia.net), hosted via GitHub Pages.

## Structure

```
index.html   ← the entire site (single file)
CNAME        ← custom domain config for GitHub Pages
```

## Deploying changes

Just edit `index.html` and push to `main`. GitHub Pages rebuilds automatically within ~30 seconds.

## DNS setup (Namecheap)

| Type  | Host | Value                |
|-------|------|----------------------|
| A     | @    | 185.199.108.153      |
| A     | @    | 185.199.109.153      |
| A     | @    | 185.199.110.153      |
| A     | @    | 185.199.111.153      |
| CNAME | www  | ltvmediapro.github.io |

HTTPS enforced via Let's Encrypt (free, auto-renews).
