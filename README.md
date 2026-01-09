# ikonqu (Twinpath Icons)

Koleksi ikon FontAwesome Pro yang dikelola secara internal oleh Twinpath. Repositori ini menggunakan format **Monorepo** untuk mengelola berbagai versi ikon.

## Struktur Paket

| Paket | Versi FontAwesome | Deskripsi |
| :--- | :--- | :--- |
| [`@twinpath/icons`](./packages/icons) | 5.15.3 | Versi stabil (Standar/Legacy) |
| [`@twinpath/icons-v6`](./packages/icons-v6) | 6.0.0-alpha.3 | Versi terbaru (Modern/Alpha) |

## Cara Penggunaan

### 1. Instalasi
Pilih salah satu versi yang diinginkan:

```bash
# Untuk v5
npm install @twinpath/icons

# Untuk v6
npm install @twinpath/icons-v6
```

### 2. Import di Proyek
```javascript
import "@twinpath/icons"; // atau "@twinpath/icons-v6"
```

## Lisensi
Aset ikon ini berbasis **FontAwesome Pro**. Repositori ini bersifat **Public** dengan nama **ikonqu**. Kode pembungkus dilisensikan di bawah **ISC License**.
