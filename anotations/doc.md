# Comandos de inicialização do Tailwind CSS
  Em sequência:

- npm i -D tailwindcss ("npm i" é abreviação de "npm install")
- npx tailwindcss init (executar o pacote tailwind CSS e e criamos o arquivo de configurações do tailwind CSS (com o init))
- criação da pasta "src" na raiz da pasta do projeto

- em seguida, vamos configurar o nosso arquivo de configurações do tailwind (tailwind.config.js)
    - content: [] recebe um caminho de uma pasta chamada src

- dentro da "src" criar um index.html com a sintaxe base do HTML 5
- ARQUIVO DE INPUT (entrada do projeto): criar um input.css e definir a linguagem (modo de exibição) do arquivo como "tailwindcss" (a extensão instalada no VSCode)
- nas settings do VSCode, procurando por file associations, adicionar um item "*.css" e dar valor de tailwindcss

- ARQUIVO DE OUTPUT (saída do projeto): npx tailwindcss -i ./src/input.css -o ./src/output.css --watch 
  -  esse arquivo de output basicamente é o que contém o tailwind, ele deve ser importado no "index.html", dessa forma ele vai fazer um rebuilding toda vez que o .html for editado.

- class="text-2xl font-bold text-red-400": é uma estilização do tailwind direto na classe, agiliza o processo de desenvolvimento e é bem clara e óbvia para se fazer, além de ter um autcomplete que te ajuda a completar o que você está estilizando.
- para abrir o localhost, 
