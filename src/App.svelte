<script>
	import Capa from "./Capa.svelte";
import Divisao from "./Divisao.svelte";
import Rodape from "./Rodape.svelte";
	import Secao from "./Secao.svelte";
</script>

<Capa />

<Divisao />

<Secao titulo="About me" centralizarTexto={true}>
	<p align="center">
		I'm a software developer who constantly seeks out innovative solutions to everyday problems. 
		I've been honing my analytical thinking and collaboration skills. 
	</p>
	<br />
	<hr />
</Secao>

<Secao titulo="Skills">
	<div>
		<h3>Languages and Databases:</h3>
		<a href="https://docs.microsoft.com/pt-br/dotnet/csharp/">
			<img alt="csharp" src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
		</a>
		<a href="https://developer.mozilla.org/pt-BR/docs/Web/CSS">
		  <img alt="css3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
		</a>
		<a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML">
		  <img alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
		</a>
		<a href="https://developer.mozilla.org/pt-BR/docs/Web/JavaScript">
		  <img alt="javascript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
		</a>
		<a href="https://docs.microsoft.com/pt-br/sql/sql-server/?view=sql-server-ver15">
		  <img alt="sqlserver" src="https://img.shields.io/badge/Microsoft%20SQL%20Sever-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white" />
		</a>
		<a href="https://www.mysql.com/">
		  <img alt="mysql" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" />
		</a>
	  </div>
	
		
	   <div>
		 <h3>Technologies:</h3>
		 <a href="https://docs.microsoft.com/pt-br/dotnet/framework/">
			<img alt=".net" src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=dot-net&logoColor=white" />
		 </a>
		 <a href="https://git-scm.com/docs/git/pt_BR">
			<img alt="git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
		 </a>
		 <a href="https://code.visualstudio.com/docs">
			<img alt="visual studio code" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />
		 </a>
		 <a href="https://docs.microsoft.com/pt-br/visualstudio/windows/?view=vs-2019">
			<img alt="visual studio" src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white" />
		 </a>
	  </div>
	  <br />
</Secao>

<Divisao />

<Rodape />
