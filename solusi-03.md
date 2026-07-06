# Solusi Crackme 3 - Bypass Register

- **Nama Tantangan:** Anti-Debug Crackme
- **Platform:** crackmes.one

### Langkah Penyelesaian:
1. Menjalankan binary di x64dbg, program langsung menutup diri karena mendeteksi debugger.
2. Memasang breakpoint pada fungsi API Windows 'IsDebuggerPresent'.
3. Melakukan patching dengan mengubah nilai kembalian register EAX dari 1 menjadi 0 untuk mengelabui program.
4. Validasi berhasil dilewati tanpa proteksi.
