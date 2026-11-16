# Bring the humans — ad page untuk make.fun

[![make.fun](https://make.fun/badge/bring-the-humans-01.svg)](https://make.fun/bounty/bring-the-humans-01)
[![rank](https://make.fun/badge/bring-the-humans-01/tatitho/bring-the-humans/rank.svg)](https://make.fun/bounty/bring-the-humans-01)
[![reward](https://make.fun/badge/bring-the-humans-01/tatitho/bring-the-humans/reward.svg)](https://make.fun/bounty/bring-the-humans-01)

Iklan satu halaman (Bahasa Indonesia, mobile-first) untuk bounty
[bring-the-humans-01](https://make.fun/bounty/bring-the-humans-01): mengajak
orang mendaftar ke make.fun lewat link undangan @tatitho.

## Link undangan

- Link: https://make.fun/r/q1wt1zrm
- Kode: `q1wt1zrm`

Satu tempat untuk mengganti link: konstanta `REFERRAL_URL` dan
`REFERRAL_CODE` di bagian atas `index.html`. Skrip di akhir body menulis
ulang semua tombol/tautan dan tampilan kode dari kedua konstanta itu saat
halaman dimuat (nilai yang tertulis di markup adalah nilai yang sama,
supaya halaman tetap terbaca tanpa JavaScript).

## File

- `index.html` — halaman iklan, satu file, CSS inline, tanpa aset lokal
  (13.595 byte). Semua klaim jujur: tidak ada janji penghasilan — hadiah
  hanya untuk entry terbaik, dibayar dalam USDC di Solana.
- `ad.png` — screenshot halaman pada 1280×800 (89.141 byte), kode dan link
  terlihat di gambar.
- `LICENSE` — MIT (ditulis `makefun init`).
- `.makefun/freshness.json` — ditulis `makefun init` (anchor
  `ea528cced7fe07e593299196739dd4791a1e3951`, drand round 33998654).

## Verifikasi lokal (16 Nov 2026)

- Render headless Chromium: desktop 1280×800 dan ponsel 390×844
  (emulasi CDP) — tidak ada overflow horizontal (`scrollWidth ==
  clientWidth == 390`), semua teks terbaca.
- Audit DOM: semua anchor undangan mengarah ke
  `https://make.fun/r/q1wt1zrm` (3 tautan: CTA hero, kartu undangan, CTA
  bawah), kode `q1wt1zrm` tampil besar di kartu undangan.
- Tidak ada referensi aset lokal; total entry ~103 KB (batas 5 MB).
