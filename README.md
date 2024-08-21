<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="Space.CSS">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
   
    <div>
        
      <nav class="navbar navbar-expand-lg navbar-light bg-black" >
        <a class="navbar-brand" id="navbar1" href="#">Home</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
                  <a class="nav-link" id="navbar2" href="#">Destination</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" id="navbar3" href="#">Technology</a>
                </li>
               
              </ul>
            </div>
          </nav>
    </div>
    
 <div>
    <div class="bg-container">
        <h1 class="head">Embark on space science</h1>
        <h1 class="head2">THAT'S ONE SMALL STEP FOR MAN, ONE GIANT LEAP FOR MANKIND.</h1>
        
        
    
</div>
   
</body>
</html>

.bg-container{
    background-image: url(shuttle.jpg);
    background-size: cover;
    height: 100vh;
    width: 100vw;
    
}
.head{
    color: aliceblue;
    text-align: left;
    position: absolute;
    top: 250px;
    text-shadow: 2px 2px 2px rgb(162, 74, 74);
    
}
.head2{
    font-size: xx-large;
    text-align: left;
    position: absolute;
    top: 450px;
    font-family: 'Times New Roman', Times, serif;
    
}
#navbar1{
    color: white;
    margin-left: 100px;
    position: fixed;
    top: 0;
    right: 0;
    width: 410px;
    font-size: larger;
    
}
#navbar2{
    color: white;
    margin-left: 100px;
    position: fixed;
    top: 0;
    right: 0;
    width: 300px;
    font-size: larger;
    
}
#navbar3{
    color: white;
    margin-left: 100px;
    margin-left: 100px;
    position: fixed;
    top: 0;
    right: 0;
    width: 150px;
    font-size: larger;
    
}
