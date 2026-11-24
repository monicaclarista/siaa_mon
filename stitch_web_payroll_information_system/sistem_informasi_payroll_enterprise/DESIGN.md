---
name: Sistem Informasi Payroll Enterprise
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45474c'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#545f73'
  primary: '#091426'
  on-primary: '#ffffff'
  primary-container: '#1e293b'
  on-primary-container: '#8590a6'
  inverse-primary: '#bcc7de'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#00171c'
  on-tertiary: '#ffffff'
  tertiary-container: '#002d36'
  on-tertiary-container: '#009db7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e3fb'
  primary-fixed-dim: '#bcc7de'
  on-primary-fixed: '#111c2d'
  on-primary-fixed-variant: '#3c475a'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1rem
  label-numeric-lg:
    fontFamily: JetBrains Mono
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.02em
  label-numeric-md:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
  label-numeric-sm:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
  label-caps:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 1rem
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  margin: 1.75rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style
Sistem desain ini ditujukan untuk aplikasi enterprise Human Capital Management (HCM) dan Payroll berbasis desktop web. Karakter visual memancarkan presisi institusional, keandalan mutlak, kepatuhan finansial, serta efisiensi tinggi bagi profesional HR, finance, dan auditor.

Pendekatan gaya menggabungkan **Corporate Modern** dengan ketajaman arsitektur data finansial:
- Struktur informasi berdensitas menengah-ke-tinggi (*medium-high data density*) yang tenang, teratur, dan minim distraksi.
- Kontras arsitektural antara navigasi utama bernuansa *Deep Navy* (kestabilan & otoritas) dan area kerja bernuansa *Crisp Light Slate* (fokus & keterbacaan data).
- Tata letak disiplin dengan grid tabular yang tegas, indikator status deterministik, dan pemisahan hierarki visual yang jelas untuk angka-angka perhitungan gaji, PPh 21, BPJS, dan tunjangan.

## Colors
Palet warna dirancang untuk memenuhi standar aksesibilitas WCAG AA/AAA pada antarmuka finansial dan kepegawaian.

### Skema Warna Utama
- **Primary (`#1E293B` / Slate 800) & Canvas Dark (`#0F172A` / Slate 900):** Menopang sidebar navigasi, header modal institusional, serta teks heading level tertinggi.
- **Secondary Corporate Blue (`#2563EB` / Blue 600):** Aksi primer (*call-to-action*), tab aktif, fokus input, dan tautan dokumen/slip gaji.
- **Tertiary Cyan Highlight (`#06B6D4` / Cyan 500):** Penanda sorotan analitik, grafik realisasi kas payroll, dan progress bar kalkulasi massal.
- **Neutral Surface & Background:**
  - App Canvas: `#F8FAFC` (Slate 50)
  - Card & Container Surface: `#FFFFFF` (Pure White)
  - Borders & Dividers: `#E2E8F0` (Slate 200)
  - Muted Text / Caption: `#64748B` (Slate 500)
  - Body Text: `#334155` (Slate 700)

### Status Finansial & Operasional
- **Success (`#16A34A` / Green 600):** Gaji telah ditransfer (*disbursed*), validasi data lengkap, status BPJS aktif. Background badge: `#F0FDF4`, border: `#BBF7D0`.
- **Warning (`#D97706` / Amber 600):** Memerlukan verifikasi (*pending approval*), lembur tidak wajar, selisih absensi. Background badge: `#FFFBEB`, border: `#FDE68A`.
- **Danger (`#DC2626` / Red 600):** Transfer gagal (*rejected*), anomali kalkulasi pajak, terminasi mendadak. Background badge: `#FEF2F2`, border: `#FECACA`.
- **Info (`#2563EB` / Blue 600):** Draf payroll, dalam proses kalkulasi antrean. Background badge: `#EFF6FF`, border: `#BFDBFE`.

## Typography
Sistem tipografi dirancang secara modular dengan pemisahan peran tegas:
- **Inter** bertanggung jawab atas kejelasan struktural antarmuka: header modul, navigasi, tabel header, teks deskripsi, dan form label.
- **JetBrains Mono** didedikasikan secara ketat untuk nominal mata uang (IDR), nomor rekening, Nomor Induk Kependudukan (NIK), kode akun buku besar (GL Code), serta persentase tarif pajak. Font monospace tabular memastikan nilai angka sejajar secara vertikal (*right-aligned*) tanpa pergeseran lebar karakter saat dipindai dalam tabel transaksi.

### Aturan Tipografi
- Seluruh nilai moneter pada tabel dan ringkasan pembayaran wajib menggunakan level `label-numeric-*` dan diratakan kanan (*text-align: right*).
- Heading tabel (*table header*) menggunakan `label-caps` dengan transformasi huruf kapital (*uppercase*) dan warna netral medium (`#64748B`).

## Layout & Spacing
Aplikasi dioptimalkan untuk desktop web (resolusi target minimum 1280×800 hingga 1920×1080):
- **Struktur Shell:** Sidebar navigasi tetap (*fixed*) selebar 260px pada sisi kiri (atau mode ciut/collapsed 72px), header atas selebar 64px, dan area konten utama yang dapat bergulir secara independen.
- **Grid Konten:** Menggunakan 12-kolom fluid grid di dalam area konten utama dengan batas lebar maksimum (*max-width*) 1600px untuk mempertahankan keterbacaan data.
- **Margin & Gutter:** Margin luar konsisten pada `1.75rem` dan gutter antar kartu KPI atau kolom data pada `1.25rem`.
- **Rhythm Finansial:** Jarak vertikal antar baris dalam data grid payroll dipertahankan pada 40px–44px untuk densitas optimal tanpa mengurangi akurasi klik pada baris aksi.

## Elevation & Depth
Hierarki visual ditekankan melalui pelapisan permukaan (*tonal layering*) dan garis batas subtil (*subtle borders*), bukan bayangan tebal. Hal ini menjaga performa visual tetap tajam pada lembar kerja berisi ribuan sel data.

- **Level 0 (Kanvas Dasar):** `#F8FAFC` — latar belakang seluruh aplikasi.
- **Level 1 (Card & Data Grid):** Latar `#FFFFFF` dengan batas tegas 1px `solid #E2E8F0` dan bayangan ambient mikro: `0 1px 3px 0 rgba(15, 23, 42, 0.05)`.
- **Level 2 (Dropdown, Popover, Floating Filter):** Latar `#FFFFFF`, border 1px `#CBD5E1`, bayangan menengah: `0 4px 6px -1px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
- **Level 3 (Modal Dialog & Batch Processing Drawers):** Latar `#FFFFFF`, bayangan dalam berpenetrasi tinggi: `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.08)` dengan backdrop overlay `rgba(15, 23, 42, 0.6)`.

## Shapes
Sistem ini menggunakan tingkat kelengkungan **Soft (Level 1)**:
- Sudut elemen interaktif standar (tombol, input teks, badge, checkbox) menggunakan kelengkungan `0.25rem` (4px).
- Kontainer modul utama, panel statistik (*KPI summary cards*), dan modal dialog menggunakan kelengkungan `0.5rem` (8px / `rounded-lg`).
- Pendekatan geometris bersudut tegas ini mencerminkan karakter spreadsheet dan perangkat lunak akuntansi enterprise, menghindarkan kesan kasual atau terlalu bulat (*bubble-like*).

## Components

### 1. Tombol (Buttons)
- **Primary Button:** Latar `#2563EB`, teks `#FFFFFF`, hover `#1D4ED8`, padding `0.5rem 1rem`, font `Inter` Medium 14px. Digunakan untuk aksi konfirmasi kritis (misal: "Proses Payroll", "Terbitkan Slip").
- **Secondary / Outline Button:** Latar `#FFFFFF`, border 1px `#CBD5E1`, teks `#334155`, hover background `#F8FAFC`. Digunakan untuk aksi filter, ekspor Excel, atau kembali.
- **Destructive Button:** Latar `#DC2626`, teks `#FFFFFF`, hover `#B91C1C`. Digunakan untuk pembatalan batch atau penghapusan master data.
- **Button Sizing:** Standar enterprise 36px height untuk efisiensi ruang layar desktop.

### 2. Badge Status Payroll
- Berbentuk kapsul bersudut lunak (radius 4px), padding `0.125rem 0.5rem`, font `Inter` Bold 11px uppercase.
- Menggabungkan titik indikator (*dot indicator*) 6px di sebelah kiri teks status.
- Contoh:
  - `Draft`: Teks `#475569`, Background `#F1F5F9`, Dot `#94A3B8`
  - `Disetujui`: Teks `#15803D`, Background `#F0FDF4`, Dot `#22C55E`
  - `Tertunda`: Teks `#B45309`, Background `#FFFBEB`, Dot `#F59E0B`
  - `Gagal Bayar`: Teks `#B91C1C`, Background `#FEF2F2`, Dot `#EF4444`

### 3. Data Tables & Buku Besar (Ledger Grid)
- **Header:** Latar `#F8FAFC`, border bawah 2px `#E2E8F0`, teks `label-caps` rata tengah/kiri, kecuali kolom nilai moneter yang wajib rata kanan (*right-aligned*).
- **Rows:** Latar `#FFFFFF`, zebra striping opsional pada `#FBFCFD`, border bawah 1px `#F1F5F9`, hover row state `#F8FAFC`.
- **Numeric Cell:** Wajib menggunakan font `JetBrains Mono` 13px atau 14px, format ribuan Indonesia (contoh: `Rp 14.850.000,00`).

### 4. Input Fields & Form Keuangan
- Tinggi input standar 36px, radius 4px, border 1px `#CBD5E1`, latar `#FFFFFF`.
- Fokus state: Border `#2563EB` dengan cincin luar (*focus ring*) 2px `#BFDBFE`.
- Field moneter memiliki prefix tetap "Rp" dengan latar kontras `#F1F5F9` dan pemisah border vertikal internal.

### 5. Checkbox & Radio
- Ukuran 16×16px dengan radius 3px untuk checkbox dan 50% untuk radio.
- Border 1.5px `#94A3B8`, terisi `#2563EB` saat checked dengan ikon checkmark putih tajam.

### 6. Summary KPI Card
- Latar putih dengan border 1px `#E2E8F0`, padding `1.25rem`.
- Berisi label metrik (`body-sm` Muted), angka agregat moneter (`label-numeric-lg` Slate 900), serta indikator tren perubahan persentase dibanding periode payroll sebelumnya.

### 7. Modal Konfirmasi Eksekusi Payroll
- Menampilkan panel ringkasan rekapitulasi: Total Karyawan, Total Pengeluaran Bersih (*Take Home Pay*), dan Beban Pajak PPh 21 sebelum otorisasi final PIN/password supervisor.