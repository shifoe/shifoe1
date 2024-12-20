

<!DOCTYPE html>
<html lang="ar" dir="rtl">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://unpkg.com/mvp.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/earlyaccess/notonaskharabic.css">
    <title>index. html</title>
    <style>
        html, body {
            font-family: 'Noto Naskh Arabic';
            margin: 10px 20px;
        }
    </style>
</head>
<body>
<!DOCTYPE html> <html lang="ar" dir="rtl"> <head> <meta charset="utf-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <link rel="stylesheet" href="https://unpkg.com/mvp.css"> <link rel="stylesheet" href="https://fonts.googleapis.com/earlyaccess/notonaskharabic.css"> <title>كود خصم</title> <style> html, body { font-family: 'Noto Naskh Arabic'; margin: 10px 20px; background-color: yellow; } .coupon { border: 5px dashed #bbb; width: 80%; margin: 0 auto; max-width: 600px; background-color: white; text-align: center; position: relative; padding: 20px; } .coupon h1 { margin: 0; padding: 10px; background-color: #f2f2f2; } .code { padding: 20px; font-size: 20px; background-color: #e0e0e0; margin-bottom: 10px; } .copy-btn { padding: 10px 20px; background-color: #4CAF50; color: white; border: none; cursor: pointer; font-size: 16px; border: 3px solid yellow; } .copy-btn:hover { background-color: #45a049; } </style> </head> <body> <div class="coupon"> <h1>احصل على خصم 80%</h1> <div class="code" id="couponCode">E711</div> <button class="copy-btn" onclick="copyAndRedirect()">نسخ الكود والذهاب إلى الموقع</button> </div> <script> function copyAndRedirect() { var code = document.getElementById("couponCode").innerText; navigator.clipboard.writeText(code).then(function() { alert('تم نسخ الكود: ' + code); window.location.href = "https://www.noon.com/saudi-ar/"; }, function(err) { console.error('فشل النسخ: ', err); }); } </script> </body> </html>
</body>
</html>
