

# Machine-Learning-Guia-O-Reilly - Base de Dados Titanic


 <!-- Explicação do projeto -->
<h2 align="left"> 🧾 Descrição do Projeto</h2>
<p align="left"> Projetos feito para determinar se uma pessoa sobreviveu ao desastre do Titanic. A idéia é determinar o melhor modelo preditivo, com base nas métricas obtidas com algoritmos de diferentes familias e escolher qual teve o melhor resultado para ser o modelo do projeto.</p>

 <!--<h4 align="left"> Bases de Dados usadas</h4>
<p align="left">Fonte dos dados atualizada(recommended for education and development versão full): <a href="https://grouplens.org/datasets/movielens/" target="_blank" align = "center">MovieLens</a> </p>

<p align="left">Dados do kaggle: <a href="https://www.kaggle.com/tmdb/tmdb-movie-metadata" target="_blank" align = "center">Kaggle Movies Database</a> </p>-->

 <!-- Status do projeto -->
 <h2 align="left"> ⁉ Status </h2>
<h4 align="left"> 
	<p align="left"> Concluído ✅</p>
</h4>

<!-- Indice -->
<!--<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#roadmap">Roadmap</a> • 
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#contribuicao">Contribuição</a> • 
 <a href="#licenc-a">Licença</a> • 
 <a href="#autor">Autor</a>
</p>-->

<!-- Tecnologias envolvidas -->
<div align="left" class='container'>
	<h2 align="left"> 🛠 Tecnologias envolvidas</h2>
		<a href="https://www.python.org/" target="_blank" align = "left"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" width="120" height="30" alt="Python3" /></a>
		<a href="https://jupyter.org/" target="_blank" align = "left"> <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" width="120" height="30" alt="Jupyter" /></a>
		<a href="https://www.jetbrains.com/pt-br/pycharm/download/" target="_blank" align = "left"> <img src="https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green" width="120" height="30" alt="Pycharm" /></a>
	
</div>

<!-- Requirements -->
<div align="left" class='container'>
	<h2 align="left">👨‍💻 Pré-requisitos </h2>
	<p align="left">Python3 instalado</p>
  <p align="left">Jupyter instalado</p>
  	<p align="left">OU</p>
  	<p align="left">Conta no Google Colab</p>
</div>


<!-- How to execute -->
<div align="left" class='container'>
	<h2 align="left">🏃‍♀️ Como Executar este projeto? </h2>
  <p align="left"> Clone o repositorio</p>
	<p align="left"> 1. Tenha o Python3 instalado, caso execute localmente</p>
  	<p align="left"> 1. Tenha o Jupyter instalado, caso execute localmente</p>
  	<p align="left"> 1.1 Use um framework de sua preferência, Pycharm, Spider, Jupyter, etc</p>
	<p align="left"> OBS: Neste projeto foi utilizado o Pycharm</p>
  <p align="left">OU</p>
	<p align="left"> 2. Tenha uma conta no Google Colab</p>
	<p align="left"> 2.1 Crie um notebook e copie e cole os códigos nele para executar</p>
	<p align="left">Done ! ✅</p>
</div>

<!-- Resultados -->
<div align="center" class='container'>
	<h2 align="center"> ⚡Resultados ⚡</h2>
</div>

<!-- Resultados parciais -->
<div align="left" class='result'>
	<h3 align="left"> ➡ Matriz de Confusão ⬅</h3>
	<img alt="#vendas" title="#vendas" src="https://github.com/6abi/Machine-Learning-Guia-O-Reilly/blob/main/ml_pocket_reference-master/ch03/images/mlpr_0304.png" width=400" height="400"/>
    <p>Obeserva-se que a quantidade de previsões correta é bem maior do que as incorretas, porém, não é um modelo "perfeito", visto que os valores fora da diagonal não são zeros.</p>
</div>

<div align="left" class='result'>
	<h3 align="left"> ➡ Curva ROC para o algoritmo de Random Forest ⬅</h3>
	<img alt="#vendas" title="#vendas" src="https://github.com/6abi/Machine-Learning-Guia-O-Reilly/blob/main/ml_pocket_reference-master/ch03/images/mlpr_0305.png" width=400" height="400"/>
    <p>Com valor de 0.85, está acima de 0.5, considerado aceitavél.</p>
</div>

<div align="left" class='result'>
	<h3 align="left"> ➡ Curva de aprendizado para o algoritmo de Random Forest ⬅</h3>
	<img alt="#vendas" title="#vendas" src="https://github.com/6abi/Machine-Learning-Guia-O-Reilly/blob/main/ml_pocket_reference-master/ch03/images/mlpr_0306.png" width=400" height="400"/>
    <p>observa-se uma tendência crescente até um pouco mais de 800, depois disso, tem uma tendência a estabilização, portanto, a quantidade de dados da base é o suficiente para montar o modelo, não se faz necessário mais amostras.</p>
</div>
