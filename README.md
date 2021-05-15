# Whatsapp-API
Whatsapp-API Khanza-Lite-3

Tutorial Setting WA Khanza-Lite 3 dengan Whatsapp-API
Link Youtube https://www.youtube.com/watch?v=pP_QPxxznHk
1.	Download dan Install NodeJs
2.	Extract Whatsapp-API.ZIP
3.	Masuk ke Folder Whatsapp-API yang sudah di extract melalui terminal,
4.	 Jalankan Perintah npm install di terminal 
5.	Jalankan Perintah npm run start:dev
6.	Buka Browser dan ketik alamat localhost:8000 atau dll sesuai settingan
7.	Scan QRCode yang muncul dengan Handphone Anda
8.	Setting NAT Ip local anda menjadi Public diMikrotik
9.	Untuk membuat URL API anda
13.	Setting File Booking Html yang terletak di 
        Khanza-Lite/plugins/rawat_jalan/view/admin/booking.html
         Ganti URL xhttp.open("POST", "https://wa.basoro.id/send-message", true);    yang terletak di baris 164 sesuai url anda 
         Contoh : xhttp.open("POST", "https://ganti-IP-Anda/send-message", true); 
14.	 Silahkan Daftar melalui APAM dan Kirim WA dari menu Booking di Khanza Lite

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Whatsapp API Tutorial

Hi, this is the implementation example of <a href="https://github.com/pedroslopez/whatsapp-web.js">whatsapp-web.js</a>

Watch the tutorials:

- <a href="https://youtu.be/IRRiN2ZQDc8">Whatsapp API Tutorial: Part 1</a>
- <a href="https://youtu.be/hYpRQ_FE1JI">Whatsapp API Tutorial: Part 2</a>
- <a href="https://youtu.be/uBu7Zfba1zA">Whatsapp API Tutorial: Tips & Tricks</a>
- <a href="https://youtu.be/ksVBXF-6Jtc">Whatsapp API Tutorial: Sending Media File</a>
- <a href="https://youtu.be/uSzjbuaHexk">Whatsapp API Tutorial: Deploy to Heroku</a>
- <a href="https://youtu.be/5VfM9PvrYcE">Whatsapp API Tutorial: Multiple Device</a>
- <a href="https://youtu.be/Cq8ru8iKAVk">Whatsapp API Tutorial: Multiple Device | Part 2</a>
- <a href="https://youtu.be/bgxxUWqW6WU">Whatsapp API Tutorial: Fix Heroku Session</a>
- <a href="https://youtu.be/iode8kstDYQ">Whatsapp API Tutorial: Dynamic Message Reply</a>

### How to use?

- Clone or download this repo
- Enter to the project directory
- Run `npm install`
- Run `npm run start:dev`
- Open browser and go to address `http://localhost:8000`
- Scan the QR Code
- Enjoy!

### Send message to group

You can send the message to any group by using `chatID` or group `name`, chatID will used if you specify the `id` field in the form, so if you want to send by `name`, only use name.

**Paramaters:**

- `id` (optional if name given): the chat ID
- `name` (optional): group name
- `message`: the message

Here the endpoint: `/send-group-message`

Here the way to get the groups info (including ID & name):

- Send a message to the API number `!groups`
- The API will replying with the groups info
- Use the ID to send a message

## Support Me

You can make a support for this work by <a href="https://karyakarsa.com/ngekoding/">Karya Karsa</a>. Thanks
