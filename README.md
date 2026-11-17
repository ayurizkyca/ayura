# Portfolio — Ayu Rizkyca Awalia

Personal portfolio site, gaya zine/polaroid. Satu file HTML statis, tanpa build step.

**Live:** https://ayura-web.netlify.app (deploy via Netlify)

## Struktur

```
index.html    — seluruh situs (HTML + CSS + sedikit JS)
favicon.svg   — ikon tab browser
og-image.png  — gambar preview saat link dibagikan (LinkedIn/WA/dll)
foto/         — taruh foto di sini (lihat foto/README.md untuk nama file)
```

## Update situs

1. Edit `index.html` atau tambah foto di `foto/`
2. `git add -A && git commit -m "pesan" && git push`
3. Netlify auto-deploy dalam ±1 menit

## Preview lokal

Buka `index.html` langsung di browser, atau:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000
```
