# latihan_flutt5_profile

- **Nama:** Rafa Fathur Rohman
- **Matkul:** Aplikasi Mobile

---

## Debugging Log

- Memisah `main.dart` dan `profile_page.dart`.
- Pecah komponen pakai Extract Widget (`ProfileAvatar` & `ProfileInfo`).
- Ubah tipe data `count` di `StatItem` dari `int` ke `String`.
- Pakai `Expanded` di `ListView.builder` biar nggak overflow.

---

## Log Commit

### Hari 1
- **1:** `feat: inisialisasi tampilan dasar profil` (Bikin layout awal profil)
- **2:** `refactor: pemisahan komponen foto dan detail profil` (Extract widget avatar dan info)

### Hari 2
- **1:** `feat: integrasi section statistik di profil rafa` (Tambah komponen statistik)[cite: 28, 30]
- **2:** `refactor: ekstraksi komponen statistik ke ProfileStats dan StatItem` (Extract widget statistik)[cite: 29, 30]

### Hari 3
- **1:** `feat: implementasi listview builder untuk daftar project` (Bikin list project)
- **2:** `refactor: ekstraksi item daftar project ke widget ExperienceCard` (Extract widget card)