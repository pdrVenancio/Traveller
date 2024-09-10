# Trabalho Final Web

Esse é um repositório criado para armazenar os arquivos do trabalho final do curso de Programação Web.
`<br>`
`<br>`
O projeto consiste em um site para compra de passagens de avião para diversos lugares utilizando um mapa para encontrar os lugares disponíveis.`<br>` `<br>`
A página inicial é uma tela de login, com possibilidade de cadastro de novos usuários. Usamos um token de autenticação para garantir segurança de senhas e outras informações pessoais. `<br>`
Ao entrar no site, um mapa interativo surge, com diversos pontos marcados. Ao clicar em um ponto, uma tela de compra de passagens para esse local irá surgir, e o cliente pode comprar quantas passagens quiser. `<br>`
Alternativamente, caso entre como um administrador, o usuário pode realizar um CRUD com os locais no mapa, ou seja, adicionar locais novos, atualizar locais já existentes, e deletar locais desnecessários. `<br>`

# Problema solucionado

O problema solucionado pelo código seria encontrar passagens para lugares através de um mapa, o que facilita a geolocalização do usuário para encontrar o destino mais apropriado

# Porque o problema é importante?

O site facilita a compra de passagens já que exibe em um mapa a exata localização dos lugares que possuem passagens disponíveis

# Como rodar o projeto

Em ambas pastas *Back* e *Front*, algum módulos precisam ser instalados usando o npm.

<ol>
    <li> Certifique-se que seu computador possui a versão mais recente do nvm instalada. Você pode instalar o nvm seguindo as instruções presentes <a href="https://github.com/nvm-sh/nvm?tab=readme-ov-file#important-notes">neste link</a>
    <li> Entrando na pasta Front, rodar o comando <strong>npm i</strong> vai instalar todas as bibliotecas necessárias.
    <li> Ainda na pasta Front, utilizar o comando <strong>npm run dev</strong> deve ligar o Front. Um link deve ser oferecido no terminal. Esse link te leva para a página de login. Não tente entrar ainda, pois o Back continua desligado.
    <li> Entrando na pasta Back desta vez, rodamos o comando <strong>npm i</strong> novamente com a mesma intenção de antes.
    <li> Sobrando apenas ligar o Back, o comando <strong>nodemon app.js</strong> resolve o problema.
    <li> Agora, o projeto pode ser utilizado sem nenhuma complicação.
</ol>
