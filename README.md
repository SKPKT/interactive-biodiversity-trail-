# ECOVERSE • BIODIVERSITY TRAIL

**Jelajah. Belajar. Lindungi.**

Laman interaktif SK Pendidikan Khas Taiping, dengan lapan stesen pembelajaran.

## Struktur laman

```text
index.html
.nojekyll
README.md
stesen-01/index.html   Little Herb Haven
stesen-02/index.html   Rain Water Harvesting (SPAH)
stesen-03/index.html   Little Recycle Hub
stesen-04/index.html   Little STEM Lab
stesen-04/assets/      10 imej asal Little STEM Lab
stesen-05/index.html   Little Greens Haven
stesen-06/index.html   Little Compost Zone
stesen-07/index.html   Little Bloom Haven
stesen-08/index.html   Digital Knowledge Hub
```

Imej halaman lain dibenamkan dalam HTML. Semua fail dalam `stesen-04/assets/` mesti dimuat naik bersama halaman Stesen 04. Tiada proses binaan atau pemasangan pakej diperlukan.

## GitHub Pages

Dalam repository ini, buka **Settings → Pages → Build and deployment**:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**
- Klik **Save**.

Laman utama: https://skpkt.github.io/interactive-biodiversity-trail-/

Stesen boleh dibuka melalui `stesen-01/` hingga `stesen-08/`. Navigasi menggunakan pautan relatif yang menyokong laluan asas repository GitHub Pages.

## Kandungan dan kemajuan

Halaman utama berasal daripada `ECOVERSE_Biodiversity_Trail_GitHub_Ready.zip`; setiap stesen menggunakan ZIP stesen terkini yang dibekalkan. Reka bentuk, perkataan, imej, kuiz, confetti dan tepukan dikekalkan. Pelarasan membaiki pautan navigasi, sasaran pautan portal, dan nama fungsi JavaScript tidak sah pada Stesen 02 supaya interaktiviti asal dapat dijalankan.

Kemajuan disimpan menggunakan kunci `localStorage` asal dalam pelayar dan peranti yang sama. Halaman utama membaca status selesai setiap stesen. Domain pratonton tempatan dan GitHub Pages mempunyai storan yang berasingan.

Stesen 08 mengekalkan Eco Learn, Eco Explorer dan Eco Innovator serta susunan kuiz **Bayam → Bendi → Terung**.
