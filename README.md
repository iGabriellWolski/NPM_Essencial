# Introdução ao NPM

## O que é NPM?

O NPM, que significa "Node Package Manager", é um gerenciador de pacotes para o ambiente de tempo de execução JavaScript Node.js. Ele desempenha um papel fundamental no ecossistema de desenvolvimento JavaScript, permitindo que os desenvolvedores instalem, compartilhem e gerenciem facilmente as dependências de seus projetos.

## Aplicações do NPM

O NPM é amplamente utilizado em projetos web e de aplicativos para:

- Instalar bibliotecas de terceiros: Os desenvolvedores podem instalar facilmente bibliotecas JavaScript de terceiros usando o NPM, economizando tempo e esforço no desenvolvimento de seus projetos. <br>
- Gerenciar dependências de projetos: O NPM permite que os desenvolvedores listem e gerenciem todas as dependências de seus projetos em um arquivo `package.json`, simplificando o processo de desenvolvimento e colaboração.<br>
- Publicar e compartilhar pacotes: Os desenvolvedores podem publicar suas próprias bibliotecas e pacotes no registro NPM, tornando-as disponíveis para outros desenvolvedores em todo o mundo.<br>
- Automatizar tarefas de build e deploy: O NPM fornece uma série de scripts predefinidos e personalizados que podem ser executados para automatizar tarefas comuns de build, testes e deploy em projetos JavaScript.

## Comandos do NPM

### Básico

- `npm install`: Instala as dependências listadas no arquivo `package.json`.<br>
- `npm install <package>`: Instala um pacote específico do NPM localmente.<br>
- `npm uninstall <package>`: Remove um pacote instalado localmente.<br>
- `npm update`: Atualiza os pacotes para as versões mais recentes, seguindo as regras de versão definidas no `package.json`.<br>
- `npm outdated`: Mostra uma lista dos pacotes que estão desatualizados.<br>
- `npm init`: Inicializa um novo projeto NPM, criando um arquivo `package.json`.<br>
- `npm search <keyword>`: Procura por pacotes no repositório NPM com base em uma palavra-chave.<br>
- `npm publish`: Publica um pacote no registro NPM.<br>
- `npm start`: Inicia o script especificado como "start" no arquivo `package.json`.<br>
- `npm test`: Executa os testes definidos no script "test" no arquivo `package.json`.

### Intermediário

- `npm install -g <package>`: Instala um pacote globalmente, disponível em todo o sistema.<br>
- `npm uninstall -g <package>`: Remove um pacote instalado globalmente.<br>
- `npm version <version>`: Atualiza a versão do pacote especificada no arquivo `package.json`.<br>
- `npm run <script>`: Executa um script personalizado definido no arquivo `package.json`.<br>
- `npm cache clean`: Limpa o cache NPM, removendo pacotes temporários e dados armazenados em cache.

### Avançado

- `npm link`: Cria um link simbólico entre um pacote local e um projeto, útil para o desenvolvimento de pacotes NPM.<br>
- `npm audit`: Analisa as dependências de um projeto em busca de vulnerabilidades de segurança.<br>
- `npm dedupe`: Remove duplicatas de pacotes no diretório `node_modules`.<br>
- `npm prune`: Remove as dependências não utilizadas do arquivo `package.json` e do diretório `node_modules`.<br>
- `npm config`: Gerencia as configurações do NPM, como o registro padrão, proxy e cache.<br>
- `npm pack`: Empacota o projeto em um arquivo tarball, útil para distribuição ou instalação em outro lugar.<br>
- `npm ci`: Instala as dependências exatamente como estão definidas no `package-lock.json`, útil para ambientes de CI / CD ou builds determinísticos.
