# food_recipes

npm install

const QRCode = require('qrcode');
const fs = require('fs');

QRCode.toFile('少油地三鲜.png', 'https://www.youtube.com/watch?v=ZRyRSjXUk2U', (err) => {if (err)throw err;console.log('QR code saved!');});
temp_file_name = 'test.png'
QRCode.toFile(temp_file_name, 'https://www.youtube.com/watch?v=ZRyRSjXUk2U');

qr_file_name = '少油地三鲜.png'

fs.rename(temp_file_name, qr_file_name);


qr_file_name = "resources/油炸糖酥小麻花.png"
url = "https://www.youtube.com/watch?v=65b7qSQALwA"
QRCode.toFile(qr_file_name, url, (err) => {if (err)throw err;console.log('QR code saved!');});



qr_file_name = "resources/蜂蜜麻花.png"
url = "https://www.youtube.com/watch?v=4xJvylpJ5Us"
QRCode.toFile(qr_file_name, url, (err) => {if (err)throw err;console.log('QR code saved!');});
