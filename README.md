# AriesTriputranto owner directory JSON 
yaml
{
  "nama_direktori": "openssl_ca",
  "path": "/etc/pki/CA",
  "deskripsi": "Direktori utama untuk Otoritas Sertifikat (CA) OpenSSL.",
  "metadata_konfigurasi": {
    "format_serupa": "YAML atau INI",
    "versi_openssl": "3.0.0",
    "is_terproteksi": true
  },
  "konten": [
    {
      "nama": "openssl.cnf",
      "tipe": "file",
      "tujuan": "File konfigurasi utama yang mendefinisikan pengaturan dan struktur CA.",
      "ukuran_kb": 10
    },
    {
      "nama": "certs",
      "tipe": "direktori",
      "tujuan": "Menyimpan semua sertifikat yang telah diterbitkan oleh CA ini."
    },
    {
      "nama": "crl",
      "tipe": "direktori",
      "tujuan": "Menyimpan daftar pencabutan sertifikat (Certificate Revocation List)."
    },
    {
      "nama": "newcerts",
      "tipe": "direktori",
      "tujuan": "Menyimpan salinan sertifikat yang baru diterbitkan."
    },
    {
      "nama": "private",
      "tipe": "direktori",
      "tujuan": "Menyimpan kunci privat CA. Direktori ini harus memiliki izin yang sangat ketat.",
      "izin": "private-key-only"
    },
    {
      "nama": "index.txt",
      "tipe": "file",
      "tujuan": "Database yang berisi daftar semua sertifikat yang telah diterbitkan."
    },
    {
      "nama": "serial",
      "tipe": "file",
      "tujuan": "Berisi nomor seri sertifikat berikutnya yang akan diterbitkan."
    },
    {
      "nama": "crlnumber",
      "tipe": "file",
      "tujuan": "Berisi nomor seri CRL (Certificate Revocation List) berikutnya."
    }
  ]
},
{
  "nama_direktori": "proyek_utama",
  "path": "/users/AriesTriputranto/proyek_utama",
  "deskripsi": "Struktur proyek aplikasi web.",
  "metadata_yaml": {
    "version": "1.0.0",
    "developer": "AriesTriputranto",
    "last_updated": "2025-08-24T12:00:00.000Z"
  },
  "konten": [
    {
      "nama": "src",
      "tipe": "direktori",
      "isi": [
        {
          "nama": "main.js",
          "tipe": "file",
          "ukuran_kb": 250
        },
        {
          "nama": "components",
          "tipe": "direktori",
          "isi": [
            {
              "nama": "button.js",
              "tipe": "file",
              "ukuran_kb": 10
            }
          ]
        }
      ]
    },
    {
      "nama": "config",
      "tipe": "direktori",
      "isi": [
        {
          "nama": "database.yaml",
          "tipe": "file",
          "ukuran_kb": 5,
          "deskripsi_isi": "File konfigurasi database dalam format YAML."
        },
        {
          "nama": "server.yaml",
          "tipe": "file",
          "ukuran_kb": 8,
          "deskripsi_isi": "File konfigurasi server dalam format YAML."
        }
      ]
    },
    {
      "nama": "README.md",
      "tipe": "file",
      "ukuran_kb": 12
    },
    {
      "nama": "package.json",
      "tipe": "file",
      "ukuran_kb": 25
    }
  ]
},
{
  "signature": "<div>Best regards,</div><div><br></div><div><b>AriesTriputranto</b></div><div><i>Your Title or Role</i></div><div><br></div><div><a href=\"https://www.google.com\">My Website</a></div>",
  "isDefault": true,
  "display_name": "Primary Signature"
},
{
  "nama": "webroot",
  "path": "/var/www/html",
  "tipe": "direktori",
  "isi": [
    {
      "nama_pengguna": "AriesTriputranto",
      "more_account": true,
      "tipe": "direktori",
      "path": "/var/www/html/about",
      "isi": [
        {
          "nama": "index.html",
          "tipe": "file",
          "ukuran_bytes": 1024
        },
        {
          "nama": "style.css",
          "tipe": "file",
          "ukuran_bytes": 512
        }
      ]
    },
    {
      "nama": "images",
      "tipe": "direktori",
      "path": "/var/www/html/images",
      "isi": [
        {
          "nama": "logo.png",
          "tipe": "file",
          "ukuran_bytes": 8192
        }
      ]
    },
    {
      "nama": "index.html",
      "tipe": "file",
          "ukuran_bytes": 2048
        },
    {
      "nama": "app.js",
      "tipe": "file",
      "ukuran_bytes": 4096
    }
  ]
},
{
  "nama": "webroot",
  "path": "/var/www/html",
  "tipe": "direktori",
  "isi": [
    {
      "nama": "about",
      "tipe": "direktori",
      "path": "/var/www/html/about",
      "isi": [
        {
          "nama": "index.html",
          "tipe": "file",
          "ukuran_bytes": 1024
        },
        {
          "nama": "style.css",
          "tipe": "file",
          "ukuran_bytes": 512
        }
      ]
    },
    {
      "nama": "images",
      "tipe": "direktori",
      "path": "/var/www/html/images",
      "isi": [
        {
          "nama": "logo.png",
          "tipe": "file",
          "ukuran_bytes": 8192
        }
      ]
    },
    {
      "nama": "index.html",
      "tipe": "file",
      "ukuran_bytes": 2048
    },
    {
      "nama": "app.js",
      "tipe": "file",
      "ukuran_bytes": 4096
    }
  ]
},
{
  "nama_lisensi": "Apache License, Version 2.0",
  "spdx_identifier": "Apache-2.0",
  "deskripsi": "Lisensi perangkat lunak bebas yang permisif.",
  "pemegang_lisensi": {
    "nama": "AriesTriputranto",
    "organisasi": "PT. Contoh Pengembangan Perangkat Lunak",
    "tahun_hak_cipta": 2025
  },
  "persyaratan": {
    "izin_diberikan": [
      "Penggunaan komersial",
      "Modifikasi",
      "Distribusi",
      "Paten",
      "Penggunaan pribadi"
    ],
    "kondisi_diharuskan": [
      "Memberikan salinan lisensi kepada penerima",
      "Menyertakan notifikasi hak cipta dan paten",
      "Menyatakan perubahan yang dibuat pada kode",
      "Distribusi paten"
    ],
    "batasan_diberlakukan": [
      "Tidak ada jaminan (warranty)",
      "Tidak ada klaim liabilitas",
      "Tidak menggunakan nama pemberi lisensi untuk promosi"
    ]
  },
  "url_lisensi": "https://www.apache.org/licenses/LICENSE-2.0"
}




