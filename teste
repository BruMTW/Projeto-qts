<!doctype html>
<html>
<head>
       <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
	   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap-theme.min.css">   
	   <title>Teste</title> 
</head>
<body>
       <div class="col-md-6 col-offset-2">
             <div class="panel panel-primary">
                    <div class="panel-heading">Caracteres de números</div>
                    <div class="panel-body">
                           
                                  <div class="form-group">
                                        <label>Digite um numero de 1 a 20:</label>
                                        <input type="text" name="numeros" id="numeros" required minlength="1" class="form-control"/>
                                  </div>
                                  <div class="form-group">
                                        <label>Digite os caracteres:</label>
                                        <input type="text" name="caracteres" id="carac" required class="form-control"/>
                                  </div>
                                  <div class="form-group">
                                        <label>Posição do caractere selecionado:</label>
                                        <input type="text" name="posicao" id="posicao" required class="form-control"/>
                                  </div>
                                  <div>
                                        <input type="submit" id="Enviar" class="btn btn-success" value="Enviar" onclick="pegarCarac()"/>
								  </div>
								  <div id='mostrar'>
							   
									</div>
									<div id='selecionado'>
		 
									</div>
						   
						   
                    </div>
             </div>
       </div>
<body>

	<script type="text/javascript">
		
		function pegarCarac(){    
			var carac = document.getElementById('carac').value
			var separar
			separar = carac.split("")
			
			
			let caractere = []
			let numeros = document.getElementById("numeros").value
			let posicao = document.getElementById("posicao").value
			for (var i = 0; i < numeros; i++) {

				document.getElementById("mostrar").innerHTML += "<p id='letra' onclick='pegarCarac()'>" + separar[i] + ""
				document.getElementById("mostrar").innerHTML += "</p>"

				caractere.push(separar[i])
				
			} 
			console.log(caractere)
			
			console.log(caractere[posicao])
			document.getElementById("selecionado").innerHTML += "<p id='selc' onclick='pegarCarac()'> Caractere selecionado: " + caractere[posicao] 
			document.getElementById("selecionado").innerHTML += "</p>"

		}
	</script>

</body>
</html>
