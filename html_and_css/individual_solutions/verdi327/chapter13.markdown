<html>
<head>
<title>HTML &amp; CSS - Chapter 13 - Boxes Exercise</title>
<style type="text/css">

  #container {
    border: 10px solid black;
    background-color: red;
    padding: 20px;
    text-align: center;
  }

  #content{

    margin: 20px;
    padding: 5px;
    border: 5px white dotted;
    color: white;
    background-color: blue;

  }


</style>

</head>
<body>
<div id='container'>
  this div is centered<br />
  and has a 10 solid black border<br />
  and a red background<br />
  and 20 pixels of padding<br />
  <div id='content'>
    this div is centered too<br />
    and has a 20 pixel margin on the top and bottom<br />
    and 5 pixels of padding<br />
    and a 5 pixel white border<br />
    and white text so you can read it<br />
    and a blue background<br />
  </div>
</div>
</body>