<h1 align="center">
<br>
  <img src="https://o.remove.bg/downloads/00e2a1e8-14fb-43f1-b351-49b9d162f9ec/image-removebg-preview.png" alt="YOUR_PROJECT_NAME" width="280">
<br>
<br>
# Sistema de Recomendação de Livros utilizando Aprendizado de Máquina não supervisionado e o algoritmo K-NN
</h1>




* Descrição do Projeto
Este repositório contém um projeto de sistema de recomendação de livros baseado em aprendizado de máquina não supervisionado, utilizando o algoritmo de vizinhos mais próximos (K-NN - K Nearest Neighbors). O objetivo é sugerir aos usuários livros que possam ser do seu interesse, com base em padrões identificados em suas preferências anteriores e nas preferências de usuários semelhantes.

* Como funciona o sistema de recomendação?
O sistema de recomendação de livros utiliza uma abordagem colaborativa, onde as sugestões são feitas com base nas interações passadas dos usuários com os livros. Para isso, o algoritmo K-NN é aplicado aos dados de histórico de leitura de vários usuários para encontrar usuários similares com base em seus padrões de leitura.

Quando um novo usuário entra no sistema, o algoritmo K-NN é utilizado para encontrar os "k" usuários mais similares com base em seus históricos de leitura. A partir disso, o sistema recomenda os livros que esses usuários similares leram e gostaram, mas que ainda não foram lidos pelo novo usuário.

* Conjunto de Dados
O conjunto de dados utilizado neste projeto contém informações sobre os livros e os usuários. Cada usuário possui uma lista de livros que leu e uma avaliação (por exemplo, uma nota de 1 a 5) que indica o quanto gostou do livro. Os dados são tratados e pré-processados para serem utilizados no algoritmo K-NN.

* Requisitos do Ambiente
Para executar este projeto localmente, é necessário ter o seguinte ambiente configurado:
Python 3.x
Bibliotecas Python: numpy, pandas, scikit-learn

* Instruções para Execução
Clone este repositório em sua máquina local.
Certifique-se de que possui os requisitos do ambiente instalados corretamente.
Acesse a pasta do projeto e execute o script recommendation_system.py.
O sistema de recomendação será executado e poderá ser utilizado para fazer sugestões para novos usuários.

* Limitações
O sistema de recomendação de livros tem algumas limitações:

Depende fortemente dos dados disponíveis. Caso o conjunto de dados seja pequeno ou não represente adequadamente a diversidade de usuários e livros, as recomendações podem não ser tão precisas.
Não considera características dos livros ou dos usuários além das avaliações. Outras informações, como gênero, autor favorito, etc., poderiam ser usadas para melhorar as sugestões.
A escalabilidade pode ser um problema. Para grandes conjuntos de dados, o algoritmo K-NN pode se tornar lento.

