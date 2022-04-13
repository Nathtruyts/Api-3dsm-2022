[![Generic badge](https://img.shields.io/badge/STATUS%20DA%20SPRINT-CONCLUIDA-green)](https://shields.io/)
<br id="topo">
<h1 align="center"> Sprint 1: 25/03/2022 a 14/04/2022 </h1>
<p align="center"> 
    <a href="#objetivos">Objetivos da Sprint</a> | 
    <a href="#prototipo">Protótipo</a> |
    <a href="#backlog">backlog</a> |
    <a href="#entregas">Entregas</a>
    
</p>
 
<span id="objetivos">

## Objetivos

1. Viabilizar um MVP para essa sprint
    
2. Organização da equipe e planejamento de processos;
    
 - [x] Modelar o banco de dados de chamados (NoSQL)
 - [x] Programar toda a parte do backend e suas requisições
 - [x] Protipagem das telas de login e cadastro
 - [x] Construção da parte visual do envio de chamados (frontend)
 - [x] conectar todas as partes do projeto (B.D, Front e Back)
    
3. Confecção do wireframe, um rascunho do protótipo;

4. Desenvolvimento do protótipo.    
    
→ [Voltar ao topo](#topo)
    
## MVP - Mínimo Produto Viável

<p>O que vamos entregar?</p>
    
  Interface que registra e envia chamados, em sua maior parte funcional, sendo capaz de abrir, enviar, deletar e buscar chamados, através de uma interface visual conectada com um banco de dados NoSQL.
    
<span id="backlog">

## Backlog

![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/Backlog_Sprint1.png)
    
<span id="prototipo">
    
## Protótipo

![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/Tela_Cadastro.png)    
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/Tela_Login.png)    
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/Tela_Inicio.png)    
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/Tela_Chamado.png)
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/Tela_Atualizar.png)    
    
<span id="entregas">

## Entregas
    
### Back-end   
    
- [x] 2.1 - Envio de chamados: Get geral

![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/REQUISICAO_GET_CHAMADOS.png)    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/REQUISICAO_GET_CHAMADOS_RESPOSTA.png) 
    
Funcionalidade que busca e traz chamados e geral, sem uma especificação
       
- [x] 2.2 - Envio de chamados: Get ID
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/ENTRADA_GET_POR_ID.PNG)
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/GET_POR_ID_SAIDA.PNG)    

Funcionalidade que faz as buscas no banco de dados, trazendo o chamado escolhido buscado pelo id
    
- [x] 2.3 - Envio de chamados: Post
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/ENTRADA_POST.PNG)

Funcionalidade que envia as informações de chamados inseridas pelo usuário, para o banco de dados da aplicação
    
- [x] 2.4 - Envio de chamados: Put
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/POST_PEDIDO.png)
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/REQUISICAO_GET_CHAMADOS_RESPOSTA.png)
    
Funcionalidade que insere e altera os dados de chamados no banco de dados

- [x] 2.5 - Envio de chamados: Delete
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/DELETE_ENTRADA.PNG)    
    
Funcionalidade que possibilita o delete de um chamado, através de seu id.
    
- [x] 3.1 - Banco de dados: Modelagem  
    
![](https://github.com/Grupo2-DSM/Api-3dsm-2022/blob/main/img/Sprint1-CollectionChamados.png)
    
Modelagem do banco de dados para chamados, contendo os campos principais do chamado, como data, hora e relato do problema ocorrido.
    
- [x] 3.2 - Banco de dados: Conexão com backend
    
### Front-end    
    
- [x] 2.6 - Envio de chamados:Front-end
    
![]( 
    
Interface navegável por onde o usuário irá interagir com a aplicação para enviar os dados de chamados     
    
- [x] 2.7 - Conexão Frontend/backend   
       
→ [Voltar ao topo](#topo)    
