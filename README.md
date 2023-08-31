import qrcode
img =qrcode.make(
'https://www.linkedin.com/in/parshuram-singh-911261250/'
)
img.save('myQRcode.png')
