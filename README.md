ini buat admin CRUD pegawai

# Cara Menjalankan Aplikasi


http://localhost:3000/api/auth/login
{
  "username": "admin",
  "password": "admin123"
}


Menambah Data Pegawai
http://localhost:4000/api/pegawai
{
  "nama_pegawai": "Iqbal",
  "nip": "19900101202233",
  "no_ktp": "3578121234567890",
  "panggilan": "Iqbal",
  "jk": "L",
  "id_agama": 1,
  "nidn": "0000000000",
  "no_kk": "3578121234567890",
  "no_karpeg": "00000000000000",
  "gol_darah": "O",
  "id_pendidikan": "1",
  "alamat": "Jl. Contoh No. 123",
  "kota": "Surabaya",
  "kode_pos": "60111",
  "id_wil": "35781000",
  "id_kabupaten": "3578",
  "id_prov": "35",
  "telpon": "031123456",
  "handphone": "081234567890",
  "email": "pegawai@example.com",
  "email_poliban": "pegawai@poliban.ac.id",
  "website": "www.example.com",
  "id_jabatan_fungsional": 1,
  "id_jabatan_struktural": 3,
  "id_status_pegawai": "1",
  "id_bagian": 1,
  "foto": "default.jpg",
  "foto_ktp": "default.jpg",
  "foto_npwp": "default.jpg",
  "foto_karpeg": "default.jpg",
  "foto_surat_nikah": "default.jpg",
  "foto_taspen": "default.jpg",
  "foto_nip": "default.jpg"
}

http://localhost:4000/api/pegawai/{id}
{
  "nama_pegawai": "saidi",
  "panggilan": "saidi",
  "jk": "L",
  "id_agama": 1,
  "alamat": "Jl. Contoh No. 123",
  "kota": "Surabaya",
  "kode_pos": "60111",
  "id_wil": "35781000",
  "id_kabupaten": "3578",
  "id_prov": "35",
  "telpon": "031123456",
  "handphone": "081234567890",
  "email": "pegawai@example.com",
  "email_poliban": "pegawai@poliban.ac.id",
  "website": "www.example.com",
  "id_jabatan_fungsional": 1,
  "id_jabatan_struktural": 3,
  "id_status_pegawai": "1",
  "id_bagian": 1,
  "foto": "default.jpg",
  "foto_ktp": "default.jpg",
  "foto_npwp": "default.jpg",
  "foto_karpeg": "default.jpg",
  "foto_surat_nikah": "default.jpg",
  "foto_taspen": "default.jpg",
  "foto_nip": "default.jpg"
}