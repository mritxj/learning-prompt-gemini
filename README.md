# Prompt "9 Pilar Pemahaman" — IT Infrastructure Mentor

Repositori ini menyimpan riwayat pengembangan *system prompt* untuk Gemini/Claude Project
yang berfungsi sebagai mentor belajar IT Infrastructure (Linux, Cisco, MikroTik,
Virtualisasi, Keamanan Jaringan) menggunakan kerangka **9 Pilar Pemahaman**.

Prompt ini awalnya dibuat untuk persiapan lomba **LKS ITNSA**, lalu direvisi total
setelah fokus berpindah ke **persiapan kerja & interview teknis**.

---

## Struktur Direktori

```
.
├── README.md
├── Changelog.md
└── prompts/
    ├── v1.0-lks-competition-prep.md
    └── v2.0-industry-job-prep.md
```

## Versi Aktif

**v2.0 — Industry & Job Interview Prep** (`prompts/v2.0-industry-job-prep.md`)

Digunakan untuk belajar topik infrastruktur dengan output yang relevan buat kerja
sehari-hari dan buat dijelaskan ulang saat interview teknis.

## Riwayat Versi

| Versi | Tanggal | Konteks Penggunaan | Status |
|-------|---------|---------------------|--------|
| v1.0  | —       | Persiapan LKS ITNSA (standar WSC) | Arsip, tidak lagi dipakai |
| v2.0  | 2026-08-10 | Persiapan kerja & interview teknis | **Aktif** |

Detail perubahan tiap versi ada di [`Changelog.md`](./Changelog.md).

## Kenapa Repo Ini Ada

Struktur 9 pilar (Pengertian → Konsep Dasar → Alur Kerja → Analogi → Kelebihan/
Kekurangan → Tujuan → Konfigurasi → Best Practice → Tips) terbukti efektif buat
membangun pemahaman yang dalam, bukan cuma hafalan command. Yang berubah antar
versi bukan strukturnya, tapi **persona dan tujuan akhir**-nya — disesuaikan
dengan fase yang sedang dijalani (lomba vs. dunia kerja).

## Cara Pakai

1. Buka file versi yang mau dipakai di folder `prompts/`.
2. Copy seluruh isinya ke *system prompt* / instruksi custom Gemini/Claude Project.
3. Ganti `[Topik/Teknologi]` sesuai kebutuhan saat bertanya.

## Lisensi

Bebas digunakan dan dimodifikasi untuk keperluan belajar pribadi maupun komunitas.
