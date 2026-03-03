# Madogiwa Henshuu to Baka ni Sareta Ore ga, Futago JK to Doukyo suru Koto ni Natta

> Kalau kamu membiarkan kami menginap... kamu boleh melakukan hal apapun ke kita. Mitsuhiko Okaya, seorang pria biasa, dikhianati oleh istrinya dan kouhainya di kantor. Di tempat kerja, dia dihina sebagai editor tak berguna dan tenggelam dalam keputusasaan, sampai suatu hari di hadapannya muncul sepasang gadis kembar berseragam SMA yang seharusnya asing, tapi entah kenapa terasa familiar.  Si adik, Akari, ceria, aktif, dan suka menggoda dengan santai, sedangkan kakaknya, Nanako, pemalu dan canggung, tapi diam-diam mesum.  ...Mereka ternyata adalah mantan murid bimbelnya saat masa kuliah dulu.

---

## Info

| | |
|---|---|
| Judul | Madogiwa Henshuu to Baka ni Sareta Ore ga, Futago JK to Doukyo suru Koto ni Natta |
| Judul Alternatif | 窓際編集とバカにされた俺が、双子JKと同居することになった |
| Author | Ibarakino |
| Artist | Usaotome |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Shounen · Comedy · Romance · Gyaru · Slice of Life · Drama |
| Chapter | 19 chapter |

## Link

- [MangaDex](https://mangadex.org/title/a0ecce48-aa4c-48e6-8d9b-90f322a5687a/madogiwa-henshuu-to-baka-ni-sareta-ore-ga-futago-jk-to-doukyo-suru-koto-ni-natta)
- [Raw](https://comic-walker.com/detail/KC_006388_S)

---

## Struktur

```
MadogiwaHenshuu/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)