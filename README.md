<html>
<head> <title> area de un triangulo </title> </head>
<center> <h1> Calcular el area de un triangulo </h1>
<body bgcolor="red">
<script language="javascript">
function Area()
        {
     var area, base, altura;
            base = prompt("Digita la base del triágulo en metros");
            altura = prompt("Digita la altura del triángulo en metros");
            base = parseInt(base);
            altura = parseInt(altura);
            area = (base * altura)/2;
            alert("El area del cuadrado es==>" +area + "   metros cuadrados");
        }
    </script>
  <form name="form1">
      <input type="button" value="CALCULAR" onclick=Area()>
   </form>
   </center>
  </body>
</html> 
