# teste
<!DOCTYPE html>
<html>
<head>
	<title>função</title>
	<meta charset="utf-8">
	<h3>Digite seu cpf</h3>
	<input type="text" name="cpf" id="cpfi">
	<h3>Digite seu telefone</h3>
	<input type="text" name="telefone" id="tel">
	<h3>Digite seu cpf</h3>
	<input type="text" name="nome" id="nome">
	<input type="button" name="btn" id="envia" value="enviar">
	<input type="button" name="btn1" id=envia1 value="telefone">

</head>
<body>
	<script type="text/javascript">
		function retorno()
		{
			var cpf1 = document.getElementById('cpfi');
			cpf2=parseInt(cpf1.value );
			 
			if (cpf1.value ==""){
			alert(" ooocpf invalido");}
				
			alert("o cpf digitado foi " + cpf2);

		}

		 var botao = document.getElementById("envia");
	     //essa linha esta adicionando o evento click na variavel botão e pegando o valor da função Hoje
	     botao.addEventListener("click", retorno);

	     function retorno1(e)
	     {
	     	var tele = document.getElementById('tel');
	     	tele1 =parseInt(tel.value);
	     	if (tel.value =="")
			alert("Digite o telefone ");
		    tel.focus();
	     	alert("o telefone digitado é " + tel.value );
	     	
	     }
	     var botao= document.getElementById("envia1");
	     botao.addEventListener("click", retorno1);
	</script>

</body>
</html>
