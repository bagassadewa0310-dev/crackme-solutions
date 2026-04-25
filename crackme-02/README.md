# Writeup Crackme 02 - Simple Validation

- **Sumber:** [crackmes.one](https://crackmes.one)
- **Level:** Easy
- **Tools:** Ghidra

### Langkah Penyelesaian:
1. Decompile binary menggunakan Ghidra untuk melihat kode pseudo-C.
2. Ditemukan fungsi verifikasi yang membandingkan input dengan hasil operasi XOR.
3. Balikkan logika XOR menggunakan script Python pendek.
4. Serial number valid berhasil didapatkan.
