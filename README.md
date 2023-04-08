<body>
	<h1>Projeto para Recomendação de Plano de Celular da Megaline</h1>
  <h2>Objetivo</h2>
<p>O objetivo deste projeto é desenvolver um modelo de classificação para recomendar o melhor plano de celular para os clientes da Megaline, baseado em seus comportamentos mensais, usando o conjunto de dados de treinamento e validação. O modelo deve ter uma acurácia mínima de 0,75 no conjunto de teste.</p>

<h2>Fonte de Dados</h2>
<p>Os dados usados para desenvolver o modelo estão contidos no arquivo "users_behavior_upd.csv". Cada observação representa o comportamento mensal de um usuário e contém as seguintes informações:</p>
<ul>
	<li>Calls: número de chamadas</li>
	<li>Minutes: duração total das chamadas em minutos</li>
	<li>Messages: número de mensagens de texto</li>
	<li>Mb_used: tráfego de internet usado em MB</li>
	<li>Is_ultra: plano atual do usuário (Ultra - 1, Smart - 0)</li>
</ul>

<h2>Pré-processamento de Dados</h2>
<p>Os dados de origem serão divididos em três conjuntos: treinamento, validação e teste, na proporção de 60%, 20% e 20%, respectivamente. O conjunto de treinamento será usado para treinar o modelo, o conjunto de validação para ajustar os hiperparâmetros e o conjunto de teste para verificar a acurácia final do modelo.</p>

<h2>Desenvolvimento do Modelo</h2>
<p>Serão investigados diferentes modelos e hiperparâmetros para escolher o que melhor se adapta aos dados de treinamento e validação. O objetivo é obter um modelo com acurácia mínima de 0,75 no conjunto de teste. Os resultados do estudo serão descritos brevemente.</p>

<h2>Avaliação do Modelo</h2>
<p>O modelo final será avaliado usando o conjunto de teste e a acurácia será calculada. Se a acurácia for superior a 0,75, o modelo será considerado adequado para recomendar o plano de celular mais adequado aos clientes da Megaline.</p>

<h2>Considerações Finais</h2>
<p>Este projeto tem como objetivo desenvolver um modelo de classificação para recomendar o plano de celular mais adequado aos clientes da Megaline, baseado em seus comportamentos mensais. Para alcançar a acurácia mínima desejada de 0,75 no conjunto de teste, diferentes modelos e hiperparâmetros serão avaliados e o melhor modelo será selecionado. O sucesso do projeto dependerá da escolha do modelo adequado e da precisão na recomendação do plano para os clientes.</p>
</body>
</html>
