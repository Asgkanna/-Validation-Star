# -Validation-Star
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>canvas</title>
    <style>
        canvas{
            border: 1px solid red;
            margin: 50px auto;
            display: block;
        }
    </style>
</head>
<body>
    <canvas width="500" height="500"></canvas>
    <script>
        var ctx = document.getElementsByTagName("canvas")[0].getContext("2d");
          /*
          ctx.moveTo(0,0);
          ctx.lineTo(50,50);
          ctx.stroke();
          */
         /*
         ctx.font = "bold 20px arial";
         ctx.fillText("Hello IBM",0,20);
         */
        /*
        var img = new Image();
        img.src = "images/rajini.jpg";
        img.onload = function(){
            ctx.drawImage(img,0,0);
        }
        */
       /*
       */
      /*
       ctx.moveTo(100,100);
       ctx.lineTo(100,200);
       ctx.lineTo(200,200);
       ctx.lineTo(200,100);
       ctx.lineTo(100,100);

       ctx.moveTo(150,100);
       ctx.lineTO(100,200);
       ctx.lineTO(200,200);
       ctx.lineTO(150,100);
       */

       /* ctx.moveTo(100,150);
       ctx.lineTo(150,200);
       ctx.lineTo(350,200);
       ctx.lineTo(400,150);
       ctx.lineTo(100,150);
       ctx.moveTo(250,150);
       ctx.lineTo(250,20);
       ctx.lineTo(200,70);
       ctx.lineTo(250,70); */
       
       ctx.moveTo(100,10);
       ctx.lineTo(141,70);
       ctx.lineTo(218,78);
       ctx.lineTo(162,131);
       ctx.lineTo(175,205);
       ctx.lineTo(100,170);
       ctx.lineTo(41,205);
       ctx.lineTo(55,131);
       ctx.lineTo(1,78);
       ctx.lineTo(75,68);
       ctx.lineTo(100,10); 
       
       ctx.stroke(); 
    </script>
</body>
</html>
