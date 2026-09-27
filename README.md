# ECOVERSE Biodiversity Trail

GitHub Pages-ready package for SKPK Taiping.

## Struktur

```text
/
├── index.html
├── .nojekyll
├── README.md
├── stesen-01/index.html
├── stesen-02/index.html
├── stesen-03/index.html
├── stesen-04/index.html
├── stesen-05/index.html
├── stesen-06/index.html
├── stesen-07/index.html
└── stesen-08/index.html
```

## Deploy ke GitHub Pages

Repository:
`SKPKT/interactive-biodiversity-trail-`

1. Upload **kandungan folder ini terus ke root repository**.
2. Pastikan `index.html` berada di root, bukan di dalam folder tambahan.
3. Commit ke branch `main`.
4. GitHub → Settings → Pages.
5. Source: **Deploy from a branch**.
6. Branch: `main`.
7. Folder: `/ (root)`.
8. Save.

URL utama:
`https://skpkt.github.io/interactive-biodiversity-trail-/`

URL stesen:
- `/stesen-01/`
- `/stesen-02/`
- `/stesen-03/`
- `/stesen-04/`
- `/stesen-05/`
- `/stesen-06/`
- `/stesen-07/`
- `/stesen-08/`

## Nota teknikal

- Imej utama telah di-embed ke dalam HTML untuk mengurangkan masalah path.
- Pautan navigasi stesen menggunakan path relatif.
- `localStorage` lama bagi beberapa aktiviti dikekalkan untuk keserasian progress sedia ada.

Stesen 04 menggunakan sepuluh imej asal dalam `stesen-04/assets/`. Imej ini sama tepat dengan imej terbenam dalam ZIP, dan dirujuk sebagai fail berasingan untuk memastikan saiz halaman sesuai untuk muat naik GitHub.
