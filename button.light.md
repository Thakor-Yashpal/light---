<html>
  <head>
    <title>
       javascript attribute values</title>

  </head>

  <body>
    <h2> What can Javascript do ?</h2>
    
    <p>JavaScript can change HTML attribute values. </p>
    <p> in this case (js) changes the value of the src (source) attribute of  an image.</p>
    
    <button onclick="document.getElementById('myImage').src='https://sandbox-uploads.imgix.net/u/1663009503-9210e9826c7a3a2dd2213edc30af0bcf?w=600'">Turn on the light</button>

<img id="myImage" src="https://sandbox-uploads.imgix.net/u/1663009256-781144b14777d71ac4f1f3d15b8d2f4c?w=600" style="width:100px">

<button onclick="document.getElementById('myImage').src='https://sandbox-uploads.imgix.net/u/1663009256-781144b14777d71ac4f1f3d15b8d2f4c?w=600'">Turn off the light</button>

</body>
</html>
