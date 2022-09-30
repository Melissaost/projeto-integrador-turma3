
<h1 align="center"> Barba, Cabelo e Bigode </h1>

# Status do Projeto
<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>


# Descrição do Projeto
<h4 align="center"> 
    :scissors:  Projeto em desenvolvimento  :scissors:
</h4>
Aplicação desenvolvida para assinaturas mensais de serviços de beleza masculino. Serviço de assinaturas referente à planos fornecidos com parceria de diferentes barbearias no Brasil.
Os planos fornecem cortes de cabelo 💇‍♂️, cortes de barba 🧔 e serviços extras de cuidados .


# Índice 
* [Status do Projeto](#status-do-projeto)
* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades do Projeto](#funcionalidades-do-projeto)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)
* [Conclusão](#conclusão)

# Funcionalidades do Projeto
- `Funcionalidade 1`: `Cadastro do Cliente` Nosso sistema precisa estar apto a cadastrar novos clientes com seus dados inserido por eles. Para cadastrar um cliente, devem ser informados seu e-mail, válido e único dentro do sistema. Nome e dados pessoais. Todos os campos são obrigatórios.
- `Funcionalidade 1a`: `Login do Cliente` Após o cadastro do cliente, é necessário o cliente logar em uma área disponível apenas para cadastrados.
- `Funcionalidade 2`: `Visualização dos Planos Disponíveis` O usuário deve ser capaz de visualizar o preço, a quantidade de cortes de cabelo, cortes de barba e serviços extras, além de todas as vantagens dos planos.
- `Funcionalidade 2a`: `Compra de Assinatura` O usuário após analisar os planos, e escolher aquele que mais se encaixa no seu perfil de consumo, o sistema precisa processar a aquisição após a escolha do plano. Além de salvar, qual período o usuário adquirir o plano.
- `Funcionalidade 2b`: `Upgrade/Downgrade de Assinatura` O usuário pode trocar de assinatura para um plano superior, mesmo possuindo uma assinatura ativa. Porém, não pode permitir a compra de uma assinatura igual ou inferior, tendo uma assinatura ativa.
- `Funcionalidade 3`: `Visualização das Barbearias` O usuário consegue visualizar e filtrar as barbearias, com os serviços desejados, cadastradas no sistema. Além disso, clicar no endereço e redirecionar ao mapa com a rota até o local.
- `Funcionalidade 4`: :hammer: `API pras Barbearias` Quando o cliente for utilizar o produto na barbearia, a barbearia tem que ser capaz de checar se o usuário tem uma assinatura ativa e informar pro sistema quais dos serviços disponíveis o usuário utilizou e atualizar a assinatura ativa do cliente.

# Acesso ao Projeto
`Softwares necessários`
* MySQL Workbench
* Node.JS
* NPM ( Node Package Manager )

No MySQL Workbench
Abra o [scriptSQL](bancoDeDados.sql) e rode pra criar o seu banco de dados e configure o nome do root e senha no arquivo config.js no diretório database/config.js

Após fazer o download do projeto, abra seu terminal no repositório e instale as dependências do projeto.

~~~bash
npm install
~~~
`nodemon start`

# Tecnologias Utilizadas
* `Node.js`
* `MySQL`
# Pessoas Desenvolvedoras do Projeto

