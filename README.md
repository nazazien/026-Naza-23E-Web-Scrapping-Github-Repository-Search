# Web Scrapping Github Repository Search
Diunggah untuk memenuhi tugas Web Scrapping mata kuliah Pemrosesan Teks dengan menjadikan situs https://github.com/search?q=sekolah&amp;type=repositories sebagai website scrapping

! Jika token github tidak bisa diakses atau saat dijalankan hasilnya Error: 401 - Unauthorized
maka bisa ditambahkan token manual dengan cara sebagai berikut :
    1. masuk akun github Anda
    2. pilih menu Settings
    3. scroll ke bawah hingga menemukan menu Developer Settings di SideBar
    4. pilih Personal Access Token -> Tokens (Classic)
    5. klik generate new token
    6. setelah berhasil membuat token, salin token Anda kemudian tempelkan pada bagian di bawah:

    ```
    headers = {
        'Authorization': 'token Token_Anda'
    }
