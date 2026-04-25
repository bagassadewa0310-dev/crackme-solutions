# Writeup Crackme 01 - Easy Keygenme

- **Sumber:** [crackmes.one](https://crackmes.one)
- **Level:** Easy
- **Tools:** x64dbg, DIE

### Langkah Penyelesaian:
1. Cek binary menggunakan DIE untuk memastikan tidak ada packer.
2. Buka di x64dbg, cari string reference 'Wrong Password'.
3. Lihat anotasi screenshot pada area pengetesan kunci, di sana terdapat hardcoded password.
4. Masukkan password tersebut dan program berhasil di-crack.
