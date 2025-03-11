<body>
<html>
<head>
  <title>20x20 Pixel Button</title>
  <style>
    .pixel-button {
      width: 100px;
      height: 100px;
      padding: 1;
      margin: 1;&
      border: 1px solid #ccc; 
      background-color: #eee;
      font-size: 17px; 
      ui-corner: 10
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
      alert('THIS WEBSITE IS DA GOAT AND U NOT DA GOAT'); 
    });
  </script>

  
</body>
</html>
