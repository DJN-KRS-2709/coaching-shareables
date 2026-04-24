# Coaching Shareables

Public repository hosting password-protected workshop materials for coaching clients of [Dejan Krstic](https://dejan-krstic.com).

Each subdirectory under a client name contains a self-contained, encrypted HTML file served via GitHub Pages. The repository is public so GitHub Pages can serve it, but the actual content is encrypted at rest using [staticrypt](https://github.com/robinmoisson/staticrypt) — clients receive a unique password by email.

## Structure

```
<client-slug>/
  <asset-slug>/
    index.html   # staticrypt-encrypted, served via Pages
```

## Live URL

`https://djn-krs-2709.github.io/coaching-shareables/<client-slug>/<asset-slug>/`

## Encryption

All HTML in this repo is encrypted client-side. Without the password, the page shows only a prompt — the underlying content cannot be read by inspecting the source.
