# Writeup Crackme 03 - Bypass Register

- **Sumber:** [crackmes.one](https://crackmes.one)
- **Level:** Medium
- **Tools:** x64dbg

### Langkah Penyelesaian:
1. Program langsung exit saat di-debug karena ada proteksi IsDebuggerPresent.
2. Pasang breakpoint pada API Windows tersebut.
3. Patch register EAX dari 1 menjadi 0 untuk mengelabui pengecekan.
4. Proteksi bypass sukses dilakukan.
