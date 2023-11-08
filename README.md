## Criando três exemplos de diagrama de autômato finito não deterministicos.

No seguinte diagrama, só haverá um cenário de aceitação caso ele termine com BB, qualquer valor diferente deste não será aceito, mas entre S0 E S1, pode haver uma infinidade de "A" de "B", dos dois ou de nenhum dos dois.
<div align="center">
  
![image](https://github.com/andreiiasalles/Automatos/assets/57154658/a0af89b5-c5f4-4b9c-9a9e-dcf06df7d7ca)

</div>

Vamos testar os seguintes cenários:

<div align="center">
  
![image](https://github.com/andreiiasalles/Automatos/assets/57154658/ac92571f-78d0-4c02-b141-bcc6de6e182a)

</div>

Testamos a falha e o sucesso de cenários que terminam com BB e que não terminam e podemos confirmar a primeira conclusão.

<div align="center">

![image](https://github.com/andreiiasalles/Automatos/assets/57154658/661ef8ef-7337-444a-be9e-5c42cbc175e7)

</div>


### Observe outros exemplos:

- Exemplo 1:

Nesse exemplo é obrigatorio para ser aceito ter no minimo o trajeto ACA, conforme pode ser observado na imagem abaixo, Mas existe possibilidades de outros valores no intervalo de S0 para S1, S1 para S2 não conseguindo definir assim o automato. 

<div align="center">

![image](https://github.com/andreiiasalles/Automatos/assets/57154658/ce3ee5c1-c951-4cea-ac28-3ec6d261cbd6)


</div>

- Exemplo 2:

Neste exemplo existe duas possibilidades de caminhos aceitavéis, o "C" e o ABA conforme pode ser observado na imagem abaixo, mas não conseguimos determinar como será o caminho pois no intervalo entre  S0 e S1 pode haver "B" ou não e uma infinidade de "B", tornando assim não deterministico.
<div align="center">

![image](https://github.com/andreiiasalles/Automatos/assets/57154658/d5a28737-7945-4cf2-a4de-679892afc61f)


</div>


Site utilizado para criação dos diagramas e testes: https://automatonsimulator.com/
