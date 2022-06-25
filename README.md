# Simulador API

<h3> Para instalar o json-server, bastar executar o seguinte comando:</h3>

sudo npm install -g json-server
Dento do nosso projeto, vamos criar uma pasta chamada “data” dentro de “assets”

/src/assets/data
Agora crie um arquivo chamado db.json e jogue dentro da pasta “data” que acabamos de criar:

/src/assets/data/db.json
Vamos abrir o arquivo db.json e incluir o seguinte json:

<p>{</p>
 <p><p> "servidor-api": [</p>
 <p>   <p>{</p>
 <p>     <p>"id": "add 1",</p>
 <p>     <p>"Nome": "Luis Vitorino",</p>
 <p>     <p>"sexo":"Masculino",</p>
  <p>    <p>"idade": "segredo",</p>
    <p>  <p>"Instagram":"@luis.Vitorino28"</p>
    <p>},</p>
    <p>{</p>
     <p> <p>"id": "add 2",</p>
     <p> <p>"Nome": "Luis Vitorino",</p>
     <p> <p>"sexo":"Masculino",</p>
      <p><p>"idade": "segredo",</p>
      <p<p>>"Instagram":"@luis.Vitorino28"</p>
    <p>},</p>
    <p>{</p>
     <p> "id": "add 3",</p>
     <p> "Nome": "Luis Vitorino",</p>
     <p> "sexo":"Masculino",</p>
     <p> "idade": "segredo",</p>
      <p>"Instagram":"@luis.Vitorino28"</p>
    <p>},</p>
    <p>{</p>
     <p>"id": "add 4",</p>
     <p>"Nome": "Luis Vitorino",</p>
      <p>"sexo":"Masculino",</p>
      <p>"idade": "segredo",</p>
      <p>"Instagram":"@luis.Vitorino28"</p>
    <p>},</p>
    <p>{</p>
      <p>"id": "add 5",</p>
      <p>"Nome": "Luis Vitorino",</p>
      <p>"sexo":"Masculino",</p>
      <p>"idade": "segredo",</p>
      <p>"Instagram":"@luis.Vitorino28"</p>
    <p>}</p>
 <p> ]</p>
<p>}</p>
<h6> Arquivo db.json para o json-server</h6>

Nossa estrutura de pastas e o arquivo db.json ficará assim:

Estrutura de pastas com o arquivo db.json
Vamos rodar o json-server para simular nossa API REST, abra um novo terminal e na raiz do projeto execute o seguinte comando:

json-server --watch src/assets/data/db.json 
