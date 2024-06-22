# 📚 Trilha Inicial Ciência de Dados Jr
Este projeto tem como objetivo realizar uma análise básica de dados utilizando Python, explorando um conjunto de dados pré-definido para extrair insights simples através de estatísticas descritivas e visualizações gráficas.

## 💻 O Projeto
O projeto foi desenvolvido no Jupyter Notebook, a partir das bibliotecas Python, `Pandas` e `Matplotlib`, para análise e visualização dos dados com gráficos.
<br>
Para o bom funcionamento do projeto em sua máquina é necessário que instale as bibliotecas mensionadas e às importe: 
```
!pip install pandas
!pip install matplotlib
```
## 📈 Análise
Foi feita a análise de um conjunto de dados da Vendas de Cursos Online:

1. Exibindo algumas informações: **Primeiras Linhas**, o tamanho do conjunto (**colunas e linhas**) e os **tipos de dados**.

2. Estatística Descritiva Básica das colunas numéricas: **Média**, **Moda**, **Mediana** e **Desvio Padrão**.
   <br>
   
    ![image](https://github.com/Lexarlab/TrilhaDados-CodigoCerto/assets/160747907/8e4ac74b-cb60-4ae8-97ee-05d9ae6bb1b2)

3. Visualização de Dados a partir de gráficos de Barras e de Dispersão.
   <br>
   
   3.1. Nesta primeira análise foi usado o gráfico de barras para análizar a Categoria do Courso (Nome do curso) em relação a Contagem (Quantas vezes o curso aparece na tabela de Vendas). Tendo em vista que esta Contagem **não interfere** no Número de vendas dos Cursos, podemos perceber que 5 dos 10 cursos aparecem 3 vezes e o restante 2 vezes.
   <br>
   
   ![image](https://github.com/Lexarlab/TrilhaDados-CodigoCerto/assets/160747907/3a9e3f0f-2b48-4d89-9e97-8234d06e5ed0)
   <br>
   
   3.2. Na segunda análise, temos um gráfico de Dispersão da **Quantidade de Vendas** em relação ao **Preço Unitário**. Através deste gráfico é possível perceber que quanto maior o preço do curso, menor é a quantidade de curso vendido, por exemplo, o curso com o valor de 120,00 reais vendeu poucas unidades em relação ao curso com o valor de 40,00 reais que vendeu entre 45 e 50.
   <br>
   
   ![image](https://github.com/Lexarlab/TrilhaDados-CodigoCerto/assets/160747907/76544f20-3b81-4654-8229-adb58fcb8143)
   <br>

   3.3. Nesta terceira análise, foi sobre a Distribuição das Vendas ao longo do tempo, onde podemos perceber que no inicío Janeiro de 2023 entre os dias 01 e 04 e quase final entre os dias 18 à 21 **aproximadamente**, teve uma alta na quantidade de cursos vendidos, já entre os dias 05 à 17 e 23 à 31 **aproximadamente**, houve uma queda na quantidade de vendas.
   <br>
   
   ![image](https://github.com/Lexarlab/TrilhaDados-CodigoCerto/assets/160747907/8a4f2743-fe18-4bb9-a025-1f0ab67cdba1)

## 📝 Conclusão

Após as análises feitas pudemos observar que o curso mais vendido foi aquele com menor preço e que a frequência das vendas teve uma oscilação durante o mês, tendo uma queda considerável nas vendas entre o início e meio do mês.

