# python-and-HTML-CSS-js
<!DOCTYPE html>
<html>
<head>
   <title>Bali Creation </title>
    <style>
    *{
     margin:0;
     padding:0;
     font-family:Century Gothic;
     }
      .header{       
      background-image:linear-gradient(rgba(0,0,0,0.5px),rgba(0,0,0,0.5px)),url(Bali.jpg);  
      background-size:cover;
      background-position:center;       
      }
      ul{
      position:absolute;
       float:left;
       list-style-type:none;
        margin:10px;
       }
      ul li{
        display:inline-block;
      }8
    ul li a{
    text-decoration:none;
     color:945;
      padding:2px 10px;
      border:1px solid #fff;
     transition:0.6s ease;
    }
    ul li a:hover{
       background-color:#fff;
     color:#000;
     }
      ul li.active a{
       background-color:#fff;
     color:#000;
     }
     .logo {
      position:absolute;
     left:145%;
       top:85px;  
         font-size:22px;   
       color:#bb689;
      }
       .main{      
        max-width:1200px;
        margin:auto;
        }
         .title {
          position:absolute;
          top:70%;
         left:60%;
         transform:translate(-50%,-50%);
       }
         .title h1{
         color:#fff;
         font-size:50px;
           }
          .button{        
          position:absolute;
          top:80%;
         left:50%;
         transform:translate(-50%,-50%);
           }
        .btn{
         border:1px solid #fff;
         padding:2px 10px;
         color:#fff; 
         text-decoration:none;
          transition:0.6s ease;
         }
         .btn:hover {
         background-color:#fff;
         color:#000;
        }
   </style>
</head>
<body>    
   <header>      
    <div class="main">      
    <div class="logo ">BALIOTIC</div>
    <ul>   
     <li class="active"><a href="#">Home</a></li>
     <li><a href="#">Gallery</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">Contact</a></li>
     </ul> 
 <img src="Bali.jpg" style="height:600px ;width:600px;" > </div> 
       <div class="title">
      <h1>BALI WEB CREATION'S</h1>
    </div>
     <div class="button">
      <a href="#" class="btn">Welcome</a>
       <a href="#" class="btn">Learn more</a>
     </div>    
   </header>
</body>
</html>
