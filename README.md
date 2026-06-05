# prompt-coding
Buatkan aplikasi Android bernama ANZZZ TUNER.

PENTING:

JANGAN membuat API backend.
JANGAN membuat database.
JANGAN membuat koneksi server.
JANGAN membuat endpoint.
JANGAN menghubungkan ke Firebase.
JANGAN menghubungkan ke MySQL.

Buat aplikasi dalam kondisi OFFLINE / DEMO MODE.

Saya akan menghubungkan database, API, config, dan server sendiri nanti.

TUJUAN:

Buat kerangka aplikasi Android lengkap dengan UI premium, navigasi, model data lokal, halaman, dan sistem placeholder sehingga nanti mudah dihubungkan ke backend.

TEKNOLOGI:

- Flutter Stable
- Material Design 3
- Riverpod
- Responsive Mobile
- Android Only

DESAIN:

- Steam Mobile Style
- Dark Gaming Theme
- Neon Purple
- Neon Cyan
- Glassmorphism
- Smooth Animation
- Premium Modern UI

FITUR:

HOME PAGE

- Banner Slider Dummy
- Trending Games
- Popular Games
- Installed Games
- Search Bar
- Device Information

GAME PAGE

Tampilkan data dummy:

- Nama Game
- Banner
- Icon
- Package Name
- Version
- Status

CONFIG PAGE

Tampilkan data dummy:

- Anti Lag
- FPS Boost
- Balanced
- Extreme Performance
- Ultra Graphics

Semua menggunakan data lokal JSON dummy.

TWEAK PAGE

Tampilkan kategori:

- Gaming Mode
- Battery Mode
- Performance Mode
- Daily Mode

Semua menggunakan data contoh lokal.

DOWNLOAD PAGE

Tampilkan:

- Download History
- Install History

Menggunakan dummy data.

PROFILE PAGE

Tampilkan:

- Username
- Avatar
- Membership

Dummy data.

ADMIN MODE UI

Buat halaman admin lokal tanpa backend.

Menu:

- Manage Games
- Manage Configs
- Manage Tweaks
- Manage Banners

Semua hanya UI dan model data lokal.

ARSITEKTUR:

Pisahkan folder:

lib/

├── core/
├── models/
├── services/
├── providers/
├── screens/
├── widgets/
├── themes/
├── routes/
├── dummy_data/

Buat model terpisah:

GameModel
ConfigModel
TweakModel
BannerModel
UserModel

Buat service dummy:

GameService
ConfigService
TweakService

Semua mengambil data dari file JSON lokal.

NAVIGASI:

Bottom Navigation:

- Home
- Games
- Tweaks
- Downloads
- Profile

KUALITAS KODE:

- Clean Architecture
- Reusable Widgets
- Null Safety
- Modular Structure
- Mudah dihubungkan ke API di masa depan

OUTPUT YANG DIINGINKAN:

1. Source code Flutter lengkap.
2. Struktur folder profesional.
3. APK Demo Build.
4. File README.md lengkap.
5. Dokumentasi cara menghubungkan API sendiri.
6. Dokumentasi lokasi yang harus diubah untuk koneksi database.
7. Semua data menggunakan JSON dummy lokal.
8. Tidak boleh ada backend ataupun database bawaan.

Tambahkan komentar di seluruh kode:

// CONNECT YOUR API HERE

// CONNECT DATABASE HERE

// REPLACE WITH REAL DATA

agar mudah dikembangkan nanti.
Buat README.md yang menjelaskan:

- Cara build APK
- Cara mengganti dummy data menjadi API
- Cara menghubungkan Laravel backend
- Cara menghubungkan MySQL
- Lokasi file yang harus diedit
- Struktur proyek lengkap

Jelaskan seolah proyek ini akan diserahkan kepada developer lain untuk dilanjutkan.
