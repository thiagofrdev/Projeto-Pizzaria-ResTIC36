# Site da Pizzaria da Estação

Este é um projeto de um site fictício de uma pizzaria desenvolvido com técnicas de responsividade em CSS e com funcionalidades em TypeScript para o carrinho de compras e a seleção do tipo de pizza no menu. Este site foi desenvolvido como um mini projeto avaliativo para Unidade 3 (JavaScript) da Residência em Software TIC36

# Instruções para Executar o Projeto

Para executar o projeto do site da pizzaria, siga os passos abaixo:

## 1. Clonar o Repositório

1. **Abra o Terminal ou Prompt de Comando**:
   - No Windows, você pode usar o **Prompt de Comando** ou **Git Bash**.
   - No macOS ou Linux, use o **Terminal**.

2. **Clone o Repositório**:
   - Execute o comando abaixo para clonar o repositório para o seu computador:
     ```bash
     git clone git@github.com:thiagofrdev/Projeto-Pizzaria-ResTIC36.git
     ```
   - Este comando criará uma cópia local do repositório no diretório atual.

3. **Navegue até o Diretório do Projeto**:
   - Entre no diretório do projeto clonado:
     ```bash
     cd Projeto-Pizzaria-ResTIC36
     ```

## 2. Abrir o Projeto no Visual Studio Code

1. **Abra o Visual Studio Code**:
   - Inicie o Visual Studio Code no seu computador.

2. **Abra o Diretório do Projeto**:
   - No VS Code, clique em **File** (Arquivo) > **Open Folder** (Abrir Pasta).
   - Navegue até o diretório `Projeto-Pizzaria-ResTIC36` e selecione-o.

## 3. Executar o Projeto com Live Server

1. **Instale a Extensão Live Server** (se ainda não estiver instalada):
   - No VS Code, vá para a aba de **Extensões** (ícone de quadrado no lado esquerdo ou pressione `Ctrl+Shift+X`).
   - Pesquise por **"Live Server"**.
   - Clique em **"Install"** para instalar a extensão.

2. **Inicie o Live Server**:
   - Com o projeto aberto no VS Code, clique com o botão direito do mouse no arquivo `index.html` na aba do Explorer à esquerda.
   - Selecione **"Open with Live Server"** no menu de contexto.
   - O Live Server abrirá uma nova aba no seu navegador padrão com o site executando.

Agora você pode visualizar e interagir com o site da pizzaria em tempo real enquanto faz alterações no código. Se precisar de ajuda com mais alguma coisa, não hesite em perguntar!


## Tecnologias Utilizadas
**HTML5**: Para a estruturação da página.

**CSS3**: Para estilização e responsividade do layout.

**TypeScript**: Para adicionar funcionalidades interativas ao carrinho de compras e seleção de pizzas.

## Estrutura do Projeto
O projeto é estruturado da seguinte forma:

    /build: Contém os arquivos estáticos prontos para uso.
        /imgs: Imagens utilizadas no site.
        /js: Arquivos JavaScript gerados a partir dos arquivos TypeScript.
        /pages: Páginas HTML
        /styles: Arquivos CSS para estilização.
        index.html.

    /src: Contém o código-fonte TypeScript.
        script.ts: Arquivo TypeScript com a lógica do carrinho e seleção de pizzas.

    tsconfig.json: Configurações do TypeScript.

## Possíveis Melhorias Futuras

- Integração com Backend: Adicionar um banco de dados para gerenciar pedidos e usuários.
- Página dedicada ao Carrinho: Implementar uma página específica para armazenar os pedidos.
- Melhorias na Responsividade e Desgin: Otimizar ainda mais a visualização e o design para dispositivos móveis e diferentes tamanhos de tela.

##

Obrigado por conferir o projeto! Se você tiver alguma dúvida ou sugestão, não hesite em entrar em contato.