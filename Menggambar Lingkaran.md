# Menggambar Lingkaran

Penggambaran lingkaran di lakukan menggunakan method utama
arc(x,y,r,start,stop). Start adalah awal penggambaran dan stop adalah akhir penggambaran dengan satuan radian

Berikut contoh penggambaran lingkaran yang berpusat di (95,50)
dengan jari-jari 40 pixel dan bermula dari sudut radian o ke 2π dengan mengganti bagian kode JavaScript pada kode pada contoh 2.9.5.1 di atas
simpan kodenya ke dalam file canvasLingkaaran.html.

```
<HTML>
	<HEAD>
		<TITLE> Canvas Lingkaran </TITLE>
	</HEAD>
	<BODY>
		<canvas id="myCanvas" width="200" height="100"
			style="border:1px solid #000000;">
		</canvas>
		<script>
			var c=document.getElementById("myCanvas");
			var ctx=c.getContext("2d");
			ctx.beginPath();
			ctx.arc(95,50,40,0,2*Math.PI);
			ctx.stroke();
		</script>
	</BODY>
</HTML>

```

## Output


![image](https://raw.githubusercontent.com/SansDev-Comunity/Pengenalan-HTML/refs/heads/main/img/Canvas%20Lingkaran.png)
