Showing Thumbnail

```
<!DOCTYPE html>
<html>	
	<head>
		<title>Thumbnail</title>		
	</head>
	<body>	
		<form>
			<input type="file" id="input" name="input_file" onchange="handleFiles(this.files)" />			
		</form>
		
		
		<img width="300px" id="image" src="default.png"/>
		<!--  -->

		<script type="text/javascript">
			function handleFiles(files) {
				const file = files[0]; 			 
				const reader = new FileReader();
				
				if (file.type.startsWith('image/')){ 
					reader.onload = function (e) {
			        // get loaded data and render thumbnail.
			        console.log(e);
			        document.getElementById("image").src = e.target.result;
				    };
				    // read the image file as a data URL.
				    reader.readAsDataURL(file); 
				}			    
			}
		</script>
	</body>
</html>
```


![image A](https://raw.githubusercontent.com/SansDev-Comunity/Pengenalan-HTML/refs/heads/main/img/thumbnail.png)

![image B](https://raw.githubusercontent.com/SansDev-Comunity/Pengenalan-HTML/refs/heads/main/img/thumbnail%20gambar%20b.png)
