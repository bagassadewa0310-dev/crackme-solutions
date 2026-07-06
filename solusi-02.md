# Solusi Crackme 2 - Simple Validation

- **Nama Tantangan:** JMP Validation Challenge
- **Platform:** crackmes.one

### Langkah Penyelesaian:
1. Membuka file executable menggunakan Ghidra untuk melihat dekompilasi kode C.
2. Menemukan fungsi verifikasi serial number yang menggunakan operasi logika XOR sederhana.
3. Membuat script Python pendek untuk membalikkan (reverse) operasi XOR tersebut.
4. Berhasil mendapatkan serial number yang valid.
