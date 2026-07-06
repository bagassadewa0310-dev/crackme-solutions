# Solusi Crackme 1 - Easy Keygme

- **Nama Tantangan:** Crackme Level 1
- **Platform:** crackmes.one

### Langkah Penyelesaian:
1. Melakukan analisis statis menggunakan Tools Detect It Easy (DIE) untuk memastikan file tidak di-pack.
2. Membuka file binary di dalam x64dbg dan mencari string reference 'Wrong Password' atau 'Success'.
3. Menemukan fungsi percabangan kondisi hardcoded password pada alamat memori utama.
4. Berhasil mendapatkan key/flag asli untuk menyelesaikan tantangan.
