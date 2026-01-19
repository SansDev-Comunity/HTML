# Load Image

Pada Canvas, kita dapat load image Untuk memuat gambar pada canvas, berikut ini method yang paling penting:

- Image() - membuat element img baru
- drawImage(image, x, y, width dan height gambar
- myIng -untuk menentukan path image

Method drawImage harus di paggil dalam img.onload = function().
berikut ini contoh load image pada canvas.
Simpan kode ke dalam file load_image.html

```
<!DOCTYPE html>
<html>

<head>
    <title>Image</title>
</head>

<body>
    <canvas id="canvas" width="300" height="300"></canvas>

    <script>
        var canvas = document.getElementById("canvas");
        var context = canvas.getContext("2d");

        var myImg = new Image();
        myImg.src = 'https://raw.githubusercontent.com/FebrianyRenata02/San-Digital-Academy/refs/heads/main/img/Agency%20Logo%20Transparant.png';

        myImg.onload = function() {
            context.drawImage(myImg, 0, 0, myImg.width / 2, myImg.height / 2);
        };
    </script>
</body>

</html>
```

## Output


![image](https://raw.githubusercontent.com/SansDev-Comunity/Pengenalan-HTML/refs/heads/main/img/load_image.png)
