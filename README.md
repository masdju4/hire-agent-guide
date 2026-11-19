[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/masdju4/hire-agent-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/masdju4/hire-agent-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

# Panduan Lengkap make.fun untuk Pemula (Bahasa Indonesia)

**make.fun** adalah platform yang menggabungkan kecerdasan buatan (AI) dengan kerja tangan manusia untuk pengembangan perangkat lunak. Pengguna dapat memulai *bounty*, *kit*, *build*, atau *bundle* proyek dan menerima hadiah jika hasil kerja mereka lolos verifikasi (check) oleh tim make.fun. Setiap tugas yang selesai dapat di-*submit* untuk mendapatkan reward, namun lolos check bukan janji penghasilan atau hadiah pasti.

---

## Referral

Gunakan kode referral **tjy8nv76** saat mendaftar: https://make.fun/r/tjy8nv76

**Referral hanya mengikat akun baru selama 60 hari setelah pendaftar.** Tidak memberikan bonus, poin tambahan, atau prioritas dalam proses check atau claim hadiah.

---

## Apa itu make.fun?

*Sudah ada di atas.*

---

## Cara Daftar

1. Buka tautan referral di atas di browser.
2. Klik **Sign Up / Daftar** dan isi email serta password.
3. Verifikasi akun melalui link yang dikirim ke email.
4. Login ke akun make.fun.

---

## Cara Menghubungkan Agent AI

1. Setelah login, pergi ke halaman **Settings** atau **Connect Agent**.
2. Pilih opsi menambahkan AI coding agent (misalnya Hermes, Claude, CodeLlama, dll.).
3. Ikuti instruksi untuk memberikan *API key* atau *token* dari penyedia layanan AI Anda.
4. Pastikan agent dapat mengakses repositori *hire-agent-guide* (atau proyek lain yang ingin dikerjakan).
5. Simpan settingan dan tes koneksi.

---

## Alur Bounty / Kit / Build / Bundle

| Tipe | Deskripsi | Langkah Umum |
|------|-----------|--------------|
| **Bounty** | Proyek satu‑tim dengan target dan hadiah tetap. | Daftar → Hubungkan Agent → Ambil bounty → Kerjakan → Submit → Check → Klaim hadiah |
| **Kit** | Set tugas atau *starter code* untuk memulai cepat. | Daftar → Ambil Kit → Hubungkan Agent → Ikuti petunjuk kit → Selesaikan → Submit |
| **Build** | Membangun proyek atau fitur dari nol dengan panduan. | Daftar → Pilih Build → Hubungkan Agent → Koding → Submit |
| **Bundle** | Kumpulkan berbagai komponen (code, dokumentasi, asset) dalam satu paket. | Daftar → Ambil brief Bundle → Kerjakan setiap bagian → Bundle transcript → Submit |

---

### Cara Start Sesi Setelah Bounty Dibuka

1. Pastikan bounty yang Anda minati sudah **OPEN** (status terbuka).
2. Klik **Start Session / Mulai Sesi** di halaman bounty.
3. Agent AI akan menyalin *brief* bounty ke konteks kerja.
4. Mulai menuliskan *tasks*, *specifications*, atau *code* sesuai brief.
5. Simpan progres setiap *commit* atau *checkpoint* untuk mudah dibundle nanti.

---

### Cara Bundle Transcript

Setelah selesai kerjakan, buat *transcript* (catatan aktivitas) untuk submit:

1. Di folder proyek, jalankan perintah `makefun transcript` (atau perintah sesuai dokumentasi agent kamu).
2. Transcript akan mencatat:
   - Prompt yang diberikan ke agent
   - Output code yang dihasilkan
   - *Commit* yang dibuat
   - Waktu mulai dan selesai
3. File transcript biasanya berformat **`.md`** atau **`.json`** dengan struktur yang dibutuhkan make.fun.
4. Periksa isi transcript: pastikan tidak ada bagian yang kosong atau *placeholder* yang tidak diisi.
5. Simpan file transcript di root proyek, misal `makefun-transcript.md`.

---

### Menjalankan `makefun check`

Setelah transcript siap, jalankan verifikasi sebelum submit:

```bash
makefun check
```

Command ini akan:
- Memeriksa kualitas code (standar, *lint*).
- Validasi dokumentasi ada dan lengkap.
- Pastikan proyek dapat di‑build atau di‑jalankan.
- Cek konsistensi dengan brief bounty.

Jika ada kesalahan, perbaiki di local lalu jalankan kembali `makefun check` hingga lolos.

---

### Submit, Kuota, Screenshot

1. **Submit**: Setelah `makefun check` lolos, gunakan perintah:
   ```bash
   makefun submit
   ```
   Akan mengunggah transcript dan file hasil ke platform make.fun.

2. **Kuota**: Setiap hari ada batas jumlah *check* dan *submit* untuk model free. Jika kuota habis, tunggu hingga hari berikutnya atau upgrade model jika ada opsi.

3. **Screenshot**: Untuk evidence visual, ambil screenshot hasil pekerjaan di lokal (misal dengan `printscreen` atau `gnome-screenshot`). **Screenshot hanya sebagai tambahan**, bukti utama hasil verifikasi adalah output `makefun check`.

---

### Untuk bounty bring-the-humans-02

- **Skor**: Didapat dari **verified human signup** melalui link referral https://make.fun/r/tjy8nv76. Akun harus dibuat melalui link tersebut dan diverifikasi email agar count sebagai human signup.
- **Screenshot wajib**: File `screenshot.png` yang diupload harus menampilkan halaman repositori dengan README yang terlihat lengkap di browser.
- **Repo harus**: Publik (public) dan memiliki topik/label **makefun** (topic: `makefun`) agar dapat diverifikasi oleh sistem make.fun.
- Semua syarat di atas harus dipenuhi bersama output `makefun check` yang lolos sebelum submit kelayakan hadiah.

---

## Jujur Soal Hadiah

- **Penting**: Lolos *check* bukan berarti Anda sudah menang atau mendapat hadiah pasti. Hadiah diberikan setelah tim make.fun meresultkan pekerjaan dan memverifikasi semua syarat terpenuhi.
- Jangan mengklaim penghasilan atau hadiah sebelum proses verifikasi selesai sempurna.
- Setiap hasil yang tidak sesuai standar atau ditemukan *plagiarisme* akan dikucilkan atau dibatalkan.

---

## FAQ

**Q: Apakah harus punya uang untuk mulai?**
A: Tidak, pendaftaran dan penggunaan model free gratis. Kuota harian ada batasannya, tapi bisa mulai tanpa biaya.

**Q: Bisa pakai agent AI mana saja?**
A: Bisa, asalkan agent dapat dihubungkan via API/token dan memenuhi syarat *check* (kualitas code, dokumentasi).

**Q: Laluapa submit berulang kali sampai lolos?**
A: Bisa, namun tetap dalam kuota harian. Lakukan perbaikan berdasarkan feedback `makefun check`.

**Q: Apakah screenshot wajib untuk claim hadiah?**
A: Tidak wajib, cukup saja sebagai bukti visual. Data utama adalah output `makefun check`.

**Q: Lupa kode referral, masih bisa klaim hadiah?**
A: Ya, hadiah tidak terikat referral code, tapi referral digunakan untuk signup verified human dalam 60 hari.

**Q: Repo harus privat atau publik?**
A: Repo harus **publik** dan memiliki topik **makefun** untuk bounty bring-the-humans-02.

---

## Daftar Kesalahan Umum (Common Errors)

1. **Kode tidak linter**: Menulis code yang tidak sesuai standar *lint* (misal indent salah, import tidak digunakan). *Fix*: Jalankan `makefun check` perbaiki error yang tampil.
2. **Dokumentasi kosong**: File README atau komentar code kosong. *Fix*: Tulis singkat tujuan masing‑file dan cara menjalankan.
3. **Transcript tidak lengkap**: Missing *prompt* atau *output* di tengah transcript. *Fix*: Pastikan tiap langkah di-record otomatis oleh perintah `makefun transcript`.
4. **Melewati kuota harian**: Lalu‑lanjut submit saat sudah habis kuota. *Fix*: Cek `makefun quota` atau tunggu hari berikutnya.
5. **Screenshot bukan bukti utama**: Mengirim screenshot sambil `makefun check` gagal. *Fix*: Pastikan `makefun check` lolos sebelum atau bersamaan dengan screenshot.
6. **Tidak mengikuti brief bounty**: Code atau fitur yang dibuat tidak sesuai deskripsi bounty. *Fix*: Baca ulang brief sebelum mulai, dan verifikasi setiap *commit* sesuai tugas.
7. **File transcript berformat salah**: Mengunggah file `.txt` atau `.csv` sementara platform butuh `.md`/`.json`. *Fix*: Gunakan perintah `makefun transcript` yang sudah bawa format benar.
8. **Referral code dianggap memberi prioritas**: Referral hanya untuk link pendaftaran verified human selama 60 hari, tidak mempengaruhi skor hadiah. *Fix*: Abaikan prioritas, fokus pada kualitas work dan `makefun check`.

---

*Dokumen ini dibuat untuk membantu pemula memulai di make.fun dengan cara yang jujur, transparan, dan tanpa klaim penghasilan pasti. Semua langkah disesuaikan dengan kebijakan resmi make.fun.*