# sampleWebPage.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <script src="https://kit.fontawesome.com/ef1ae5f8d0.js" crossorigin="anonymous"></script>

<link rel="stylesheet" href="Sample.css">
  <title>Suvojit's Sample</title>
  <style>
    
@import url('https://fonts.googleapis.com/css2?family=Muli&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400&display=swap');


* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color: rgba(22, 22, 22, 0.98);
  color: rgb(101, 135, 148);
  font-family: 'Roboto', sans-serif;
  letter-spacing: .5px;
  font-weight: bolder;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  overflow: hidden;
  margin: 0;
}


.container {
  background-color: rgb(236, 240, 240);
  width: 65.6%;
  height: 83%;
}

.side-Nav {
  background-color: rgba(255, 255, 255, 0.473);
  box-shadow: 2px 5px 10px rgba(121, 120, 120, 0.76);
  
  text-align: center;

  min-width: 71px;
  height: 475px;
  
}


.list_Items{
  display: flex;
  flex-direction: column;
  gap: 10px;
  list-style: none; 
  font-size: 8px;  
}

.item {
  margin-top: 17px;  
}


i {
  font-size: 1rem;
}

.main {
  display: flex;
  flex-direction: column;
  width: 100%;  
}

.upload {
  width: 115px;
  height: 110px;
  background-color: rgba(255, 255, 255, 1);
  
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 35px;
  margin-left: 110px;

  font-size: 4px;
  font-weight: bolder;
}

.blank_header {
  background-color: rgb(252, 252, 252);
  width:100%;
  height: 70px;
}
.blank_header .shadow {
  box-shadow: 2px 5px 10px rgba(173, 173, 173, 0.8);
  height: 2px;
}

.img_position {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 66px;
  width: 71px;
  box-shadow: 2px 5px 20px rgba(199, 199, 199, 0.8) ; 
  color: black;  
}

.videos{
  font-size: 9px;
  font-weight: 800;
  display: flex;
  flex-direction: row;
  gap: 5px;
  padding: 21px;
  margin-left:7px ;
}

input {
  display: block;
  text-decoration: none;
  border: none;
  width: 72%;
  font-weight: bolder;
  font-family: 'Muli', sans-serif;
  font-size: 9px;
  padding: 9px;
  border-radius: 8px;
  margin-left: 112px;
  margin-top: 8px;
  box-shadow: 2px 5px 50px rgba(216, 213, 213, 0.8);
 
}
  </style>

</head>
<body>
    <div class="container">
      <div class="blank_header">
        <div class="shadow"></div>
        <div class="img_position">
          <i style="font-size: 2rem;" class="far fa-dot-circle"></i>
        </div>
      </div>

      <div class="body" style="display:flex;position: relative;"> 
          <div class="side-Nav">
            <ul class="list_Items">
            
            

              <li class="item">
                <i class="far fa-user"></i>
                <p>Students</p>
              </li>

              <li class="item">
                <i class="fas fa-list-ul"></i>
                <p>Lesson Plan</p>
              </li>

              <li class="item">
                <i class="fas fa-cog"></i>
                <p>Settings</p>
              </li>
             
            </ul>
          </div>

          
          <div class="main">
          
            <section  class="videos">
                <i class="fas fa-caret-left" style="font-size: 15px;">              
                </i>
                <h3>Videos</h3>           
            </section>
          
            <form action="">
              <input type="text" name="" id="" placeholder="Insert URL here">
            </form>
           
            <div class="upload">
              <h1 style="color: black;">upload</h1>
            </div>

            <h3 style="font-size: xx-small; color: black;margin-left: 393px;position: absolute;top: 123px;">or</h3>
         </div>
        </div>
    </div>
</body>
</html>






