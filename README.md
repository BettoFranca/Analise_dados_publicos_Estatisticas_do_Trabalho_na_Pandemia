<br id="topo">

<h1 align="center"> Análise de estatísticas do trabalho CAGED - 2020 e 2021. </h1>

<p align="center"> 
    <a href="#userstories">User Stories</a> &nbsp | &nbsp 
    <a href="#graficos">Alguns gráficos</a> &nbsp | &nbsp 
    <a href="#dados">Base de dados utilizadas</a> &nbsp | &nbsp 
    <a href="#notebook">Como rodar a aplicação</a> &nbsp | &nbsp 
    <a href="#equipe">Equipe</a> &nbsp | &nbsp 
    <a href="#conclusao">Conclusão</a>
</p>
   
A análise de estatísticas do trabalho foi feito para exibir ao público as mais variadas estatísticas sobre o mundo do trabalho em 2020/2021. Fazemos análises de diversos tipos,
tais como: Gênero, Classe Social, Setores, Escolaridade e Faixa Etária.
Em nossas análises podemos perceber alguns indicios do quanto a pandemia interferiu no mercado de trabalho, e como aos poucos o mundo vem voltando ao "novo normal". 🌎

Esse notebook está sendo desenvolvido para a disciplina de "Estrutura de dados", ministrada pelo professor Fernando Masanori, do curso de Análise e Desenvolvimento de Sistemas, no ano de 2021, na FATEC de São José dos Campos - SP.

<span id="userstories">

## 📰 User Stories

![User Stories](https://github.com/BettoFranca/Analise_dados_publicos_Estatisticas_do_Trabalho_na_Pandemia/blob/main/Documentos/user_stories/user_stories.png)
  
  → [Voltar ao topo](#topo)

<br>

<span id="graficos">
  
## 📊 Alguns gráficos 
### (Acesse mais clicando no arquivo "Estatisticas_do_Trabalho.ipynb" do repositório)

<br>
<br>

### Total de pessoas empregadas de Maio de 2020 até Novembro de 2020. (De acordo com o PNAD) (Números na casa do MIL)

 ![Total de pessoas empregadas de Maio de 2020 até Novembro de 2020. (De acordo com o PNAD) (Números na casa do MIL)](https://github.com/BettoFranca/Analise_dados_publicos_Estatisticas_do_Trabalho_na_Pandemia/blob/main/Documentos/alguns_graficos/Total%20de%20pessoas%20empregadas%20MAI2020%20-%20NOV-2020.PNG)

<br>
<br>

### Pessoas empregadas por gênero de Maio de 2020 até Novembro de 2020. (De acordo com o PNAD)

 ![Pessoas empregadas por gênero de Maio de 2020 até Novembro de 2020. (De acordo com o PNAD)](https://github.com/BettoFranca/Analise_dados_publicos_Estatisticas_do_Trabalho_na_Pandemia/blob/main/Documentos/alguns_graficos/Pessoas%20empregadas%20por%20gênero%20MAIO2020%20ate%20NOVEMBRO2020.PNG)

<br>
<br>

### Pessoas desempregadas por faixa etária de Maio de 2020 até Novembro de 2020. (De acordo com o PNAD)

  ![Pessoas desempregadas por faixa etária de Maio de 2020 até Novembro de 2020. (De acordo com o PNAD)](https://github.com/BettoFranca/Analise_dados_publicos_Estatisticas_do_Trabalho_na_Pandemia/blob/main/Documentos/alguns_graficos/Pessoas%20desempregadas%20por%20faixa%20etaria%20MAI2020%20ate%20NOVEMBRO2020.PNG)

<br>
<br>

### Pessoas desempregadas por nível de escolaridade de Maio de 2020 até Novembro de 2020. (De acordo com o PNAD)

  ![Pessoas desempregadas por nível de escolaridade de Maio de 2020 até Novembro de 2020. (De acordo com o PNAD)](https://github.com/BettoFranca/Analise_dados_publicos_Estatisticas_do_Trabalho_na_Pandemia/blob/main/Documentos/alguns_graficos/Pessoas%20desempregadas%20por%20nivel%20de%20escolaridade%20MAIO2020%20ate%20NOVEMBRO2020.PNG)


  → [Voltar ao topo](#topo)
  
<br>
  
<span id="dados">

## 🗞️ Fonte dos dados:
1. [Arquivos CAGED Movimentações disponíveis em:](https://ftp.mtps.gov.br/pdet/microdados/NOVO%20CAGED/Movimenta%E7%F5es/2021/Abril/)
2. [Arquivo PNAD disponível em:](https://github.com/BettoFranca/Analise_dados_publicos_Estatisticas_do_Trabalho_na_Pandemia/blob/main/Documentos/bases_de_dados/pnad_covid19_202011_trabalho_BR_GR_UF.xlsx)
3. [Pesquisa Mensal de Comércio IBGE](https://github.com/BettoFranca/Analise_dados_publicos_Estatisticas_do_Trabalho_na_Pandemia/blob/main/Documentos/bases_de_dados/pmc_202104_05.xls)
  
  → [Voltar ao topo](#topo)

 <br>

<span id="notebook">

## 💾 Manipulando o notebook

### Requisitos
Python 3.8 +
Pandas
Matplotlib
Jupyter Notebook

## Instalando
1. Baixar e instalar o Python 3.8.x pelo [site oficial](https://www.python.org/downloads/)
2. Adicionar o python as [variáveis de ambiente](https://datatofish.com/add-python-to-windows-path/)
3. Clonar esse repositório 
```
git clone https://github.com/BettoFranca/Analise_dados_publicos_Estatisticas_do_Trabalho_na_Pandemia.git
```
4. Entrar na pasta do repositório (pelo cmd ou terminal) e instalar as dependências

```
pip install -r requirements.txt
```
5. Executar o Jupyter Notebook
```
jupyter notebook
```

→ [Voltar ao topo](#topo)

<br>

<span id="equipe">
	
## :busts_in_silhouette: Responsáveis
Toda a equipe está linkada pelo seu GitHub pessoal, são alunos da Fatec São José dos Campos que, ministradas pelo professor Fernando Masanori desejam trazer informações reais sobre a empregabilidade no Brasil! Time Composto por 5 pessoas, são elas: 
  
  [Daniel Vargas Ribeiro](https://github.com/DanVargaa/),
  <br>
   [Edryan Matheus](https://github.com/edryan25/),
  <br>
  [José Alberto](https://github.com/BettoFranca/),
  <br>
  [Kevin Gabriel Alves de Melo](https://github.com/kevingabrielmelo/),
  <br>
  [Luiz Miguel Macedo Andre](https://github.com/Salitop/).

→ [Voltar ao topo](#topo)

<br>

<span id="conclusao">  
  
## 🔎 Conclusão

 Ao realizar esse trabalho, nós percebemos que os homens sempre estão a frente quando se trata de emprego, em um país que tem aproximadamente 51% de mulheres, e 49% de homens, não faz sentido ter tamanha diferença quando o assunto são os empregos. 🤷‍♀️
Percebe-se também que foram demitidas várias pessoas durante o caos da pandemia em 2020, e somente agora, esse número volta a crescer e o país volta a contratar pessoas. 📑
Também é notório que os gráficos que mais abaixaram durante a pandemia, foram os das mulheres, ou seja, em uma crise os patrões preferem demitir primeiro as mulheres!
A questão empregabilidade no Brasil ainda é bem complicada, muitas pessoas sofrem com o desemprego e precisam buscar meios de sobreviver para não passar fome, durante a pandemia isso se alastrou ainda mais, e somente agora, o país vem conseguindo se acertar para voltar ao estágio zero na busca de um país com boa empregabilidade dos habitantes!
	
 → [Voltar ao topo](#topo) 
