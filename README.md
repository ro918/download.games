<body>
<html>
<head>
  <title>20x20 Pixel Button</title>
  <style>
    .pixel-button {
      width: 100px;
      height: 100px;
      padding: 0;
      margin: 0;&
      border: 1px solid #ccc; 
      background-color: #eee;
      font-size: 17px; 
      cursor: pointer; 
    }
  </style>
</head>
<body>
  <button class="pixel-button">Do NOT Click This button</button>

  <script>
    const button = document.querySelector('.pixel-button');

    button.addEventListener('click', () => {
      // Perform an action on button click
      alert('Button clicked!'); 
    });
  </script>
</body>
</html>
 	
