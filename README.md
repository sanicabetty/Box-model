<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Box Model</title>

  <style>
  
    p {
      margin: 0;
    }

    
    .box {
      width: 200px;
      height: 200px;
      box-sizing: border-box;
      display: inline-block;
    }

    
    .box1 {
      background-color: cadetblue;
      padding: 20px;
      border: 10px solid black;
    }

    
    .box2 {
      background-color: gold;
      border-top: 20px solid black;
      border-bottom: 20px solid black;
      border-left: 10px solid black;
      border-right: 10px solid black;
    }

    
    .box3 {
      background-color: indianred;
      border: 10px solid black;
    }

    
    .box2, .box3 {
      margin-top: -10px; 
      margin-left: -10px;
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="box box1">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at sapien porttitor urna elementum lacinia. 
        In id magna pulvinar, ultricies lorem id, vehicula elit. Aliquam eu luctus nisl, vitae pellentesque magna. 
        Phasellus dolor metus, laoreet ac convallis sit amet, efficitur sod dolor.
      </p>
    </div>
    <div class="box box2"></div>
    <div class="box box3"></div>
  </div>

</body>
</html>
