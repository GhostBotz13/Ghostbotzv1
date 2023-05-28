### 乂 Pesan Non-Media

```Javascript

// mengirim pesan

client.reply(m.chat, 'Halo semuanya!', m)

// atau

m.reply('Halo semuanya!')

// kirim teks \w thumbnail

client.sendMessageModify(m.chat, 'Halo semuanya!', m, {

   judul: 'Ini adalah judul',

   iklan: benar,

   jempol besar: benar,

   thumbnail: menunggu Func.fetchBuffer('https://telegra.ph/itsukabotz-04-28'),

   url: 'https://chat.whatsapp.com/HK3auSY2bb68WVdNXDUFgp'

})

// kirim reaksi

client.sendReact(m.chat, '🕒', m.key)

// kirim daftar

baris const = [{

   judul: 'Perintah A',

   barisId: '.a'

   deskripsi: ``

}, {

   judul: 'Perintah B',

   barisId: '.b'

   deskripsi: ``

}]

client.sendList(m.chat, 'Ini tajuk', `Halo semuanya!`, '© Ghostbotz', 'Ketuk!', [{

   baris

}], M)

         

// tombol kirim teks

tombol const = [{

   buttonId: `.a`,

   tombolTeks: {

      displayText: 'Perintah A'

   },

   tipe 1

}, {

   buttonId: `.b`,

   tombolTeks: {

      displayText: 'Perintah B'

   },

   tipe 1

}]

client.sendButtonText(m.chat, 'Halo semuanya!', '© Ghostbotz', tombol)

```
