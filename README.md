<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Google Chrome</title>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.3/css/all.css" integrity="sha384-SZXxX4whJ79/gErwcOYf+zWLeJdY/qpuqC4cAa9rOGUstPomtqpuNWT9wdPEn2fk" crossorigin="anonymous">
    <style>
    h1{
      font-size: 40px;
      text-align: center;
      color: red;
      margin-top:100px;
      
    }
    img{
      margin-left: 15px;
    }
    body{
      background-color: black;
    }
    a{
      color: white;
    }
    </style>
  
</head>

<body>
  
 <h1 id="greet"></h1>

  <script>
alert('السلام علیکم ورحمتہ اللّٰہ وبرکاتہ');
    function displayGreeting(){
      var time = new Date();
      var hrs = time.getHours();
      var msg = "";

      if(hrs >= 5 && hrs <= 11){
        alert('Good Morning...dear student...!');
      }else if(hrs >= 12 && hrs <= 16){
        alert ('Good Afternoon...dear student...!');
      }else if(hrs >= 17 && hrs <= 19){
        alert('Good Evening...dear student...!');
      }else{
        alert('Good Night... dear student...!');
      }

     /* document.getElementById("greet").innerText = msg;*/
     
    }

    // ایک بار چلاؤ
    displayGreeting();

    // ہر گھنٹے بعد دوبارہ اپڈیٹ (تاکہ دن کے حساب سے greeting بدل جائے)
    setInterval(displayGreeting, 60 * 60 * 1000);
    
    var a = prompt('     Enter Your Password');
 
 if(a==7662){
   
   document.write("<h1><a href= https://github.com/KaisarAsim/Ayesha-Islamic-Education-Centre-.git>اهلا وسهلا مرحبا<br >Welcome to Ayesha Islamic Education Centre😊</a>");

 }else{
  document.write('<marquee behavior="smooth" direction="left" loop="5"><h1>Wrong password<br><br>Who are you?<br><br> This is Kaisar...!</h1></marquee>');
 }
  </script>

</body>

</html>
