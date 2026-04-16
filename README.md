<!DOCTYPE html>
<html lang="en">
    <HEAD>
    <meta charset="UTF-8">
    <title> FASHION COATS</title>
    </HEAD>
    <STYLE>
        *{
            MARGIN:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, Helvetica, sans-serif;
        
        }
        body{
            background-color: rgb(41, 170, 209);
            
        }
        .tabs{
            display:flex;
            
            justify-content:space-around;
            padding:20px;
            font-size:14px;
            letter-spacing:2px;
            background-color:   rgb(7, 16, 18);
        }
        .tabs a:HOVER{
            text-decoration:none;
            color:rgb(25, 206, 191);
            cursor:pointer;
        
            
        }
        .tabs a{
            color:#e1f7fa;
            text-decoration:none;
        }
        #pics{display: inline;
            justify-content: end;


        }
        
        .container{
            display:flex;
            justify-content:right;
            align-items:right;
            height:80vh;
        }
            
        left{
            position:fixed ;
            width:400px;
        }
        .right{width:40%;
            padding:150px;

        }
        .right h1{
            font-size: 50px;
             font-weight:bold;
        }
        .right p{
            
        
            font-size:16 px;
        }
        .star{
            PADDING:20px;
            margin:10px;
        }
        .star span{
            font-size:60px;
        color:gold;
        }
        .middle{
            display:inline-block;
            margin-top:20px;
            padding:15px 50px;
            background-color:antiquewhite;
            color:rgb(4, 118, 156);
            text-decoration:none;
            font-weight:600;
            border-radius: 20px;
        }
        .middle:hover{
            background:black;
            color:white;
        }
        .vertical{
            justify-content:space-around;   
            position:absolute;
            padding:20px;
            top:50%;
            right:10px;
            transform:rotate(90deg);
            font-size:20px;
            letter-spacing:4px;
            color:rgb(238, 244, 245);
        }
        .images{
            DISPLAY:FLEX;
            margin:10px;
              justify-content:left;
              padding:50px;
            align-items:left;
            
            
        }
        BUTTON{
           
            margin-top:20px;
            padding:15px 50px;
            background-color:antiquewhite;
            color:rgb(4, 118, 156);
            text-decoration:none;
            font-weight:600;
            border-radius: 20px;
            height: 20px;
            width: 80px;
        }
         BUTTON:hover{
            background:black;
            color:rgb(241, 227, 227);
        }
    </STYLE>
<body>
    <div class="tabs">
        <a href="#">HOME</a>

        <a href="#">VISIT</a>
        <a href="images.html">IMAGES</a>
        <a href="#">BLACK</a>
        <a href="#">FASHION</a>
    </div>
   
    <div class="container">
        
 <div class="images">
        <img src="girl2.jpg" width="60%" height="80%">
        <img src="photo (3).jpg" width="60%" height="80%">
        <img src="photo (2).jpg" width="60%" height="80%">
     
        </DIV>
        
     

        <div class="left">
            
            <div class="right">
                <h1>SUMMER COAT</h1>
                <P><B>Louve collection</B></P>
                <div class="stars">
                    <h2>LATEST STOCK</h2>
                    <span>★★★★★</span>
                    </div>
            <a href="#" class="middle">SHOP NOW</a>
        </div>
    </div>
    
    <div class="vertical">NEW NEW NEW NEW

    </div>
    
</body>

</html>

