# Bruh

 <!DOCTYPE html> 
 <html lang="en"> 
  <head> 
    <meta charset="UTF-8"> 
    <link rel="stylesheet" href="google-site-verification=kQA_sGJRTkQxGXVWkyf-E91XhHuA2R969LpNWM6qncs" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous"> 
    <title>Caja de Busqueda con efecto</title> 
  </head> 
  <body> 
    <div class="buscar-caja">
      <input type="text" name="" class="buscar-txt" placeholder="Buscar..."/> 
      <a class="buscar-btn"> 
        <i class="far fa-search"></i> 
      </a> 
    </div> 
  </body> 
</html>
    
    
    
    body {
 margin: 0;
 padding: 0;
 background: #e84118;
}

.buscar-caja {
 position: absolute;
 top: 50%;
 left: 50%;
 transform: translate(-50%, -50%);
 background: #2f3640;
 height: 40px;
 border-radius: 40px;
 padding: 10px;
}

.buscar-caja:hover > .buscar-txt {
 width: 240px;
 padding: 0 6px;
}

.buscar-caja:hover > .buscar-btn {
 background: white;
 color: black;
}

.buscar-btn {
 color: #e84118;
 float: right;
 width: 40px;
 height: 40px;
 border-radius: 50%;
 background: #2f3640;
 display: flex;
 justify-content: center;
 align-items: center;
 transition: 0.4s;
 color: white;
 cursor: pointer;
}

.buscar-btn > i {
 font-size: 30px;
}

.buscar-txt {
 border: none;
 background: none;
 outline: none;
 float: left;
 padding: 0;
 color: white;
 font-size: 16px;
 transition: 0.4s;
 line-height: 40px;
 width: 0px;
 font-weight: bold;
}
    
    
                
