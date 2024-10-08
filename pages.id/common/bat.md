# bat

> Mencetak dan menggabungkan berkas.
> Klon dari `cat` dengan sintaks berwarna dan integrasi Git.
> Informasi lebih lanjut: <https://github.com/sharkdp/bat>.

- Cetak rapi konten berkas ke `stdout`:

`bat {{jalan/menuju/berkas1 jalan/menuju/berkas2 ...}}`

- Gabungkan konten beberapa berkas ke berkas tujuan:

`bat {{jalan/menuju/berkas1 jalan/menuju/berkas2 ...}} > {{jalan/menuju/berkas_tujuan}}`

- Hapus dekorasi dan matikan fitur tampilan halaman (paging) (opsi `--style plain` dapat digantikan dengan `-p`, atau nyalakan kedua opsi dengan `-pp`):

`bat --style plain --pager never {{jalan/menuju/berkas}}`

- Sorot baris tertentu dengan warna latar belakang yang berbeda:

`bat {{-H|--highlight-line}} {{10|5:10|:10|10:|10:+5}} {{jalan/menuju/berkas}}`

- Tunjukkan segala karakter yang tak tercetak seperti spasi, tab, atau indikator baris baru:

`bat {{-A|--show-all}} {{jalan/menuju/berkas}}`

- Memberi nomor pada setiap baris keluaran:

`bat {{-n|--number}} {{berkas}}`

- Mencetak konten JSON dengan sintaks berwarna:

`bat {{-l|--language}} json {{jalan/menuju/berkas.json}}`

- Menampilkan semua bahasa yang didukung:

`bat {{-L|--list-languages}}`
