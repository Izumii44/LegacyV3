# Legacy V.3.0 

<p align="center">
      <img src="https://gcdnb.pbrd.co/images/0KrsdPvPTTxP.jpg" width="99%" style="margin-left: auto;margin-right: auto;display: block;">
</p>

This is Script of WhatsApp multi device, working with [`@whiskeysockets/baileys`](https://github.com/whiskeysockets/baileys)

## Highlights

- [✓] Easy to maintenance
- [✓] Support Multi-Device Connection
- [✓] Simple Base
- [✓] Connect with Pairing-Code
- [✓] Ai Features

## Requirements
1. [NodeJS](https://nodejs.org/en/download) 16x/17x
2. [APIKEY](https://apiruulzz.my.id)

## Support My Youtube Channel
- [RullZY](http://www.youtube.com/@Rullxzz)

### EXAMPLE INSTALL & RUN

install
```bash
npm install
```
RUN
```bash
npm start
```
use pairing code
```bash
node system/index.js --pairing
```

#### If npm install failed, try using yarn instead of npm
```bah
yarn
```
---------

## example plugins 
```js
export default {
  name: "", // plugins name, tampilkan menu, support array
  command: [""],
  tags: [""], // tags, tags plugins untuk menu// commad unutuk plugins
  use: "", // Ini Buat Example,
  run: async (m, { conn, usedPrefix, command }) => { // panggil saja apa yang kamu butuhkan
    // code kamu di sini 
  },
  owner: false, // ubah true Jika khusus owner,
  group: false, // ubah true jika Khusus group,
  private: false, // ubah true jika khusus private chat
  admin: false, // ubah true jika khusus admin
  botAdmin: false, // ubah true jika bot harus admin
  bot: false, // // ubah true jika khusus bot
  premium: false, // ubah true jika khusus premium 
}
```
---------

### Thanks To 

**DikaArt**,

**AmirulDev**,

**Allah SWT**,

**Arif**,

[**Rulzz**](https://github.com/khrlmstfa),

**Orang Tua**,

**Semua yang selalu mendukung**

---------

## Contribution
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the code, but you must include the original copyright and license notice in any copy of the project or substantial portion of it.

## Acknowledgments
Special thanks to the contributors and libraries used in building this WhatsApp bot.

Happy coding! 🚀
