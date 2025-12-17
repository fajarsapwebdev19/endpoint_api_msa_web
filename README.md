# endpoint_api_msa_web
Endpoint api msa web

# ambil data karyawan tampil 10 data dalam 1 page
```
GET https://appweb.mitrasinergi.co.id/msa/apiv1/get_karyawan
```

# ambil data karyawan berdasarkan page dan limit data
```
GET https://appweb.mitrasinergi.co.id/msa/apiv1/get_karyawan/{page}/{limit}
```

# ambil data karyawan berdasarkan id
```
GET https://appweb.mitrasinergi.co.id/msa/apiv1/get_karyawan_by_id/{id}
```

# ambil data absensi secara keseluruhan 10 data dalam 1 page
```
GET https://appweb.mitrasinergi.co.id/msa/apiv1/get_absen
```

# ambil data absensi berdasarkan page dan limit data
```
GET https://appweb.mitrasinergi.co.id/msa/apiv1/get_absen/{page}/{limit}
```

# ambil data absensi berdasarkan id karyawan default 7 hari
```
GET https://appweb.mitrasinergi.co.id/msa/apiv1/get_absen_karyawan/{id}
```

# ambil data absensi berdasarkan range tanggal
```
GET https://appweb.mitrasinergi.co.id/msa/apiv1/get_absen_karyawan/{id}/{tanggal_awal}/{tanggal_akhir}/{page}/{limit}
```


# cara penggunaan

auth menggunakan bearer token bisa di dapatkan di database msa_web.msa_token_api
