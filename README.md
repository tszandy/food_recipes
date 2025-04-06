# food_recipes

npm install

const QRCode = require('qrcode');
const fs = require('fs');

QRCode.toFile('少油地三鲜.png', 'https://www.youtube.com/watch?v=ZRyRSjXUk2U', (err) => {if (err)throw err;console.log('QR code saved!');});
temp_file_name = 'test.png'
QRCode.toFile(temp_file_name, 'https://www.youtube.com/watch?v=ZRyRSjXUk2U');

qr_file_name = '少油地三鲜.png'

fs.rename(temp_file_name, qr_file_name);