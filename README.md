# BEMmeir
matala al BEM
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BEM</title>
    <link rel="stylesheet" href="dist/style.css">

</head>
<body>
    
    
       <div class="top__Nav">
           <img src="tree1.jpg" alt="" class="profile">
           <h1 class="Meir">Meir</h1>
           <p class="loc">Tel Aviv</p>
           <img src="icons8-location-24.png" class="iconloc">
           <img src="icons8-edit-24.png" class="botn">
           <button class="search-button">
              All Resuts 
           </button>
           <div class="circle"></div>
       </div>    
        
        
            
                
            
       
       <div class="wrapper">
            <div class="box--1">
                 <img src="frenchtourist.jpg" alt="" class="profile2">
                 <p class="contactName">David</p>
                 <p class="km">6 KM</p>
            </div> 
                 
            <div class="box--2">
                <img src="mendel-rabbi.jpg" alt="" class="profile2">
                <p class="contactName">Ofer</p>
                <p class="km">2.2 KM</p>
            </div>    
                 
            <div class="box--1">
                <img src="images.jpg" alt="" class="profile2">
                <p class="contactName">Meiital</p>
                <p class="km">0.5 KM</p>
            </div>   
                 

            
             <div class="map">
                  <img src="Screen Shot 2022-01-17 at 10.29 2.png" alt="" class="map">
             </div>
       </div>
        
       <div class="bottom__Nav">
           <div class="back" >
             <img src="icons8-back-30.png" alt="">
          </div> 
          <div class="settings">
             <img src="icons8-settings-24.png" alt="">
          </div>
          <div class="messages">
             <img src="icons8-messages-30.png" alt="">
          </div>
          <div class="user">
             <img src="icons8-male-user-30.png" alt="">
          </div>
          <div class="home">
             <img src="icons8-home-24.png" alt="">
          </div>
        </div>           
                  
</body>
</html> 

/////SCSS////

body{
    position: absolute;
    width: 100%;
    height: 100%;
}
.top__Nav{
    position: relative;
    background-color: rgb(92,86,86);
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    width: 400px;
    height: 95px;
    left: 700px;
    top: 100px;
}

.profile{
    position: relative;
    border-radius: 100%;
    width: 55px;
    height: 55px;
    left: 20px;
    top: 15px;
    align-items: center;
}

.circle{
    background-color: rgb(30, 255, 0);
    width: 15px;
    height: 15px;
    left: 60px;
    top:55px;
    position: absolute;
    border-radius: 50%;
}
    


.loc{
    position: relative;
    color: white;
    font-family: Arial, Helvetica, sans-serif;
    left: 130px;
    bottom: 70px;
    font-size: 12px;
    line-height: 35px;
    
}    
    

.Meir{
    position:relative;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 15px;
    left: 30px;
    bottom: 2px;
    color: white;
}

.iconloc{
    position: relative;
    width: 20px;
    bottom: 115px;
    left: 100px;
}

.botn{
    position: relative;
    border-radius: 60%;
    background-color: #5FB2B8;
    width: 25px;
    height: 25px;
    bottom: 110px;
    left: 215px;
}

.search-button{
    position: relative;
    background-color: #5FB2B8;
    border-radius: 50px;
    width: 90px;
    height: 35px;
    bottom: 119px;
    left: 242px;
    font-family: Arial, Helvetica, sans-serif;
    color: white;
    transition: 4s;
}
.search-button:hover{
   background-color:gold;
    transition: 4s;
}
.box--1{
    position: relative;
    background-color: rgb(56,56,56);
    width: 400px;
    height: 75px;
    left: 700px;
    top: 100px;   
        } 
    .box--2{
        position: relative;
        background-color: rgb(88, 85, 85);
        width: 400px;
        height: 75px;
        left: 700px;
        top: 100px;   
    }



.profile2{
    position: relative;
    border-radius: 100%;
    width: 55px;
    height: 55px;
    left: 20px;
    top: 15px;
    align-items: center;
}



.contactName{
    position: relative;
    left: 90px;
    bottom: 45px;
    font-size: 12px;
    line-height: 35px;
    color: white;
}

.km{
    position: relative;
    left:340px;
    bottom: 90px;
    color: white;
}

.map{
    position: relative;
    width: 400px;
    height: 318px;
    left: 350px;
    top: 50px;
}
////bot-nav////
.bottom__Nav{
    position: relative;
    justify-content: space-between;
    cursor: pointer;
    background-color: rgb(82,75,75);
    border-bottom-right-radius: 20px;
    border-bottom-left-radius: 20px;
    width: 400px;
    height: 95px;
    top: 100px;
    left: 700px;
    color: #106d68;
    text-align: center;
    overflow: visible;
}

.back{
   position: relative;  
   left: -160px; 
   bottom: -10px;    
}
.settings{
    position:relative;
    left: -100px;
    bottom: 20px;

}
.messages{
    position: relative;
    left:-30px;
    bottom: 50px;
}
.user{
    position: relative;
    left: 50px;
    bottom: 82px;
}
.home{
    position: relative;
    left: 140px;
    bottom: 115px;
}
