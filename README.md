# Menampilkan Karakter/ Simbol Pada Kalimat Dengan Regex
Menampilkan karakter pada Kalimat pada file CSV dengan ribuan row dengan Regex...

# File - Indonesian Abusive and Hate Speech Twitter Text
Pada git ini hanya berisi 2 file, yaitu: 
1. data.csv yang bersumber dari
   https://www.kaggle.com/datasets/ilhamfp31/indonesian-abusive-and-hate-speech-twitter-text
2. Membaca_Simbol.ipynb (berisi code/script)

# Sofware
Google Colab

# Hasil
Bayangkan, dari ribuan row tweet, karakter khusus yang ditemukan cuma segini (tanpa duplikasi):
['>', '¸', 'ª', '¨', '/', '_', 'Â', '±', '\\', '=', '³', 'á', '*', ':', '|', '¥', 'ï', '«', '²', '`', 'Ä', '»', '}', '.', '°', '%', 'ë', "'", 'ð', '¢', '¶', 'µ', '·', '^', '-', '(', '¡', '®', '£', ';', '½', '¬', '$', '#', 'Ø', ')', 'Ù', '?', '~', 'â', ']', 'º', 'ê', '!', '¹', '&', '©', '@', '¦', '{', '\xad', '¿', '[', '¯', '"', ',', '¼', 'Ã', '§', '+', '´', 'ã', '¤']

# Kapan ini digunakan?
Logika dari pembuatan kode ini, ketika kita sudah melakukan cleansing dengan regex, alangkah baiknya dipastikan dengan membaca hasil apakah sudah bersih atau belum, jika belum, maka dibuatkan cleansing otomatis dari hasil yang ada dengan metode replace dengan space kosong berdasarkan kode yang ditemukan...

Bingung ya? sama wkwkwkw

Maksudnya gini loh... huruf = huruf.replace(variabel_kode, "")
Bingung? sama wkwkwk

intinya sih gini, dengan kamu membaca simbol yang ada dalam kalimat, kamu tahu harus pake script regex seperti apa, jd gak coba-coba, soalnya banyal newbie seperti saya yang masukin semua kode regex yang penting bisa kehapus kodenya xixixixix

# Alasan
Kenapa saya membuat ini sedangkan ini hanya proyek sederhana?
Jawaban:
1. Hanya latihan saja membuat GIT kwkwkwkw
2. Banyak orang membuat tutorial cleansing... aku mah mau yang anti mainstream wkwkwkw

# Lisensi
Bebas copy saja sesuka hati hehe
