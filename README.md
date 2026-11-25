# Rilis Installer Sekolah

Repo ini **hanya berisi rilis** installer Ekosistem SSO Sekolah (file `.exe`).
Kode sumber installer ada di [bg-dw/sekolah-installer](https://github.com/bg-dw/sekolah-installer).

## Unduh

Ambil rilis terbaru di halaman [Releases](../../releases) — unduh file
`SekolahInstaller-<versi>.exe`, jalankan di PC Windows 10/11 64-bit, lalu
ikuti wizard: kode aktivasi, data sekolah + akun admin, port.

Isi paket: SSO (wajib) + 4 side app yang bisa dipilih — e-presensi,
e-surat, e-arsip, e-tabungan. Server berjalan lokal di komputer sekolah
(Nginx + PHP + MariaDB; port 8150–8154).

## Penting: butuh kode aktivasi

Installer bisa diunduh siapa saja, tapi **tidak bisa dipakai tanpa kode
aktivasi** dari pengelola (Ayah). Satu kode = satu instalasi, sekali pakai,
diminta sekali saat instalasi pertama.

## Rilis baru

Rilis dibuat otomatis oleh GitHub Actions di repo sumber
(`bg-dw/sekolah-installer`) setiap ada tag `v*` — `.exe` hasil build
dilampirkan ke rilis dengan tag yang sama di repo ini.
