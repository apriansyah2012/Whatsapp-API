Whatsapp-API Khanza-Lite-3

Tutorial Setting WA Khanza-Lite 3 dengan Whatsapp-API
Link Youtube https://www.youtube.com/watch?v=pP_QPxxznHk
1.	Download dan Install NodeJs
2.	Extract Whatsapp-API.ZIP
3.	Masuk ke Folder Whatsapp-API yang sudah di extract melalui terminal,
4.	Node Express (npm install express -g)
5.	Node QRCode  (npm install qrcode -g)
6.	install Node Nodemon diluar folder whatsapp-api   (npm install nodemon -g)
7.	Jalankan Perintah npm install di terminal 
8.	Jalankan Perintah npm run start:dev
9.	Buka Browser dan ketik alamat localhost:8000 atau dll sesuai settingan
10.	Scan QRCode yang muncul dengan Handphone Anda
11.	Setting NAT Ip local anda menjadi Public diMikrotik
12.	Untuk membuat URL API anda
13.	Setting File Booking Html yang terletak di 
        Khanza-Lite/plugins/rawat_jalan/view/admin/booking.html
         Ganti URL xhttp.open("POST", "https://wa.basoro.id/send-message", true);    yang terletak di baris 164 sesuai url anda 
         Contoh : xhttp.open("POST", "https://ganti-IP-Anda/send-message", true); 
14.	 Silahkan Daftar melalui APAM dan Kirim WA dari menu Booking di Khanza Lite

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
