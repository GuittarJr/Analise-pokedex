# Analise-pokedex</br>
Esta é a educação aqui está uma pequena descrisão de como foi baseada a minha pesquisa, no repositório você encontra o arquivo csv que eu utilizei para pesquisa, e minha pesquisa.</br>


Desafio de Projeto: Banco de dados utilizando a biblioteca Pandas.</br>
Contato:</br>
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/geovane-dos-santos-900b84221/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/geovane.dos.santos/)

Skills utilizadas:</br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

<div align="center">
  <h1>Olá, meu nome é Geovane.. e bem vindo ao mundo Pokémon!</h1>
  <div align= "center">
  <img src="https://user-images.githubusercontent.com/19601448/192146002-8c41d03d-dd42-48f9-b5af-f478fe1d083a.png" alt ="Professor Oak">
  <div>
  
 
<p>Nesse mundo habitado por estranhas criaturas chamadas de Pocket Monsters, ou simplesmente <strong>Pokémon</strong>, toda criança que completar 10 anos de idade, pode se tornar um Treinador de Pokémons e sair à procura desses bichinhos, capturando-os, treinando-os e fazendo-os lutar para ganhar experiência.</p>
  
 <p>
   
   
  ### Pesquisa 01 - Quais são os 3 Primeiros Pokémons registrados ?
  
 <p>Para isso foi utilizado:</P>
          
          df.head(3)
    
  <p>Notamos que os três pokemons registrados na pokedex é a linha evolutiva do Bulbassaur o pokemon Inicial de planta encontrado na região de Kanto:</p>
  
  <img src="https://user-images.githubusercontent.com/19601448/192339115-0404fc5e-e965-47d0-a765-32afa4b4b32f.png" alt = "Linha evolutiva Bulbassaur"/>
  
   
   Para ter acesso detalhado entre no arquivo da pesquisa utilzado.
  
  ### Pesquisa 02 -  Quais são os 3 ultimos Pokémons registrados ?
      
  <p> Para isso foi utilizado</p>
        
          df.tail(3)
          
   <p> Encontramos os Pokémons lendário, Hoopa em suas duas formas e o Volcanion. Parecem bem fortes não ?</p>
   
   <img src="https://user-images.githubusercontent.com/19601448/192654240-fa5d0235-86da-4cfc-82e7-f438527764f3.png" alt="pokemons Lendarios"/>
   
   Você pode ter acesso detalhado na pesquisa disponível aqui no repositório.
   
    
  ### Pesquisa 03 - Quais Pokémons fazem parte da primeira geração ?
  
  <p> Hoje contamos com mais de 500 Pokémons registrados na Pokedex porem foi iniciada com o registro de 151 Pokémons, você sabe quais Pokémons fazem parte da primeira geração?</br> </br> Para isso verifiquei a coluna que indica a geração qual o pokemon foi registrado "Generation" e pedi para que o python só me mostrasse Pokémons que tivesse a geração menor que 2. <p>
                        
             df.loc[df['Generation'] < 2]
             
   
   <img src="https://user-images.githubusercontent.com/19601448/192658591-d3612a15-e694-42ad-903e-4adacc2ce4eb.jpg" alt="PokémonsKanto"/>
    
  ### Pesquisa 04 -Quantidade de Pokémon por tipo: <b>FOGO</b>, <b>PLANTA<</b> E <b>AGUA</b>.
  
 <p> A cada Geração são encontrados e armazenados vário dados sobre novos Pokémons que surgem, essa pesquisa foi feita para saber qual tipo entre Fogo, Planta e Agua tem como primeiro tipo maior quantidade de dados armazenados na Pokédex.<p>
 
 <img src="
 
 <p>Para isso, Criei uma variável e nela adicionei os dados da coluna "type 1" só as informações que eu queria.<p>
        
        variável = df[df['Type 1'] == "Tipo"]
    
  ### Top 5 Pokémons com status mais alto(por status)- Pesquisa 05.
    
<div>
