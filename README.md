<body>
	<button.style.hight'100px';




 <!DOCTYPE html>
<html>
<head>
  <title>20x20 Pixel Button</title>
  <style>
    .pixel-button {
      width: 20px;
      height: 20px;
      padding: 0;
      margin: 0;
      border: 1px solid #ccc; 
      background-color: #eee;
      font-size: 8px; 
      cursor: pointer; 
    }
  </style>
</head>
<body>
  <button class="pixel-button">Click Me</button>

  <script>
    const button = document.querySelector('.pixel-button');

    button.addEventListener('click', () => {
      // Perform an action on button click
      alert('Button clicked!'); 
    });
  </script>
</body>
</html>
 	
