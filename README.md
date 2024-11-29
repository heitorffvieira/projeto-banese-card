# 🚀 Projeto Criação de Campanhas de Cashback do Banese Card 

### 📈 A solução para o problema que o Banese Card atribuiu aos squads do Projeto Porto Digital que estão trabalhando nessa problemática, foi justamente essa: Criação de Campanhas de Cashback para tais objetivos da empresa.

### 👨‍💻 Esse sisteminha e as telas, desenvolvido por mim, seguiu ao Backlog do projeto, que está na documentação do mesmo.

## ⚙ FUNCIONAMENTO:

- Validação de Login: O usuário/administrador não consegue entrar no sistema sem fornecer o seu CPF no formato correto. Após fornecer no formato correto, ele consegue acessar o sistema.

- Quando o administrador vai tentar criar uma campanha, obrigatoriamente ele terá de inserir as informações completas, que foram inclusas no Backlog do projeto: Nome da campanha, benefício, descrição, data de início e de fim. Em seguida, ao clicar no botão "próximo", aparece o campo para o administrador dizer se a campanha terá ou não WhiteList e/ou BlackList (é obrigatório ele responder esse campo, se irá querer adicionar ou não). 

- Ao selecionar que irá querer apenas WhiteList ou BlackList, ele irá ser redirecionado para as telas das respectivas listas. Ao selecionar que irá querer os dois tipos de lista, ele irá ser redirecionado para uma tela que tem as duas listas para serem preenchidas. 

- Nessas telas de WhiteList e/ou BlackList, quando o administrador tenta clicar em alguma opção do menu lateral, aparece um campo de aviso perguntando se ele deseja cancelar a inserção da(s) lista(s). Se ele tentar criar a campanha sem fornecer as informações das respectivas listas, aparece um alert dizendo para ele fornecer as devidas informações.

- Na listas WhiteList e BlackList, tem um botão de adicionar as informações nas listas. Ao clicar, aparecerá um campo para cadastrar as informações da lista, como: Tipo de cartão, mecânica de disponibilização e descrição.

- Ao criar a campanha, automaticamente, ela irá ficar armazenada no LocalStorage e a mesma estará na página Home na lista de campanhas ativas e estará também na tela das campanhas ativas, com um botão de encerrar campanha. Ao clicar no botão de encerrar campanha, obviamente, ela vai ser encerrada e estará na página Home na lista de campanhas encerradas e na tela das campanhas encerradas. Em ambos os casos (ativas e encerradas), terão as informações das campanhas: Nome, benefício, data de início e de fim.

- A parte visual, foi feita em HTML e CSS, seguindo os padrões visuais do Banese e ao protótipo do projeto.

## 🤖 TECNOLOGIAS USADAS:

<img 
    style='padding-right: 10px' width='40px' 
    title='HTML' 
    alt='HTML5' 
    align='left' 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" />

<img 
    style='padding-right: 10px' width='40px' 
    title='CSS' 
    alt='CSS3' 
    align='left' 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" />

<img 
    style='padding-right: 10px' width='40px' 
    title='JavaScript' 
    alt='JavaScript' 
    align='left' 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" />
