# Introdução ao npm

## O que é npm?

O npm, que significa "Node Package Manager", é um gerenciador de pacotes para o ambiente de tempo de execução JavaScript Node.js. Ele desempenha um papel fundamental no ecossistema de desenvolvimento JavaScript, permitindo que os desenvolvedores instalem, compartilhem e gerenciem facilmente as dependências de seus projetos.

## Aplicações do npm

O npm é amplamente utilizado em projetos web e de aplicativos para:

- Instalar bibliotecas de terceiros: Os desenvolvedores podem instalar facilmente bibliotecas JavaScript de terceiros usando o npm, economizando tempo e esforço no desenvolvimento de seus projetos.
- Gerenciar dependências de projetos: O npm permite que os desenvolvedores listem e gerenciem todas as dependências de seus projetos em um arquivo `package.json`, simplificando o processo de desenvolvimento e colaboração.
- Publicar e compartilhar pacotes: Os desenvolvedores podem publicar suas próprias bibliotecas e pacotes no registro npm, tornando-as disponíveis para outros desenvolvedores em todo o mundo.
- Automatizar tarefas de build e deploy: O npm fornece uma série de scripts predefinidos e personalizados que podem ser executados para automatizar tarefas comuns de build, testes e deploy em projetos JavaScript.

## Comandos do npm

### Básico

- `npm install`: Instala as dependências listadas no arquivo `package.json`.
- `npm install <package>`: Instala um pacote específico do npm localmente.
- `npm uninstall <package>`: Remove um pacote instalado localmente.
- `npm update`: Atualiza os pacotes para as versões mais recentes, seguindo as regras de versão definidas no `package.json`.
- `npm outdated`: Mostra uma lista dos pacotes que estão desatualizados.
- `npm init`: Inicializa um novo projeto npm, criando um arquivo `package.json`.
- `npm search <keyword>`: Procura por pacotes no repositório npm com base em uma palavra-chave.
- `npm publish`: Publica um pacote no registro npm.
- `npm start`: Inicia o script especificado como "start" no arquivo `package.json`.
- `npm test`: Executa os testes definidos no script "test" no arquivo `package.json`.

### Intermediário

- `npm install -g <package>`: Instala um pacote globalmente, disponível em todo o sistema.
- `npm uninstall -g <package>`: Remove um pacote instalado globalmente.
- `npm version <version>`: Atualiza a versão do pacote especificada no arquivo `package.json`.
- `npm run <script>`: Executa um script personalizado definido no arquivo `package.json`.
- `npm cache clean`: Limpa o cache npm, removendo pacotes temporários e dados armazenados em cache.

### Avançado

- `npm link`: Cria um link simbólico entre um pacote local e um projeto, útil para o desenvolvimento de pacotes npm.
- `npm audit`: Analisa as dependências de um projeto em busca de vulnerabilidades de segurança.
- `npm dedupe`: Remove duplicatas de pacotes no diretório `node_modules`.
- `npm prune`: Remove as dependências não utilizadas do arquivo `package.json` e do diretório `node_modules`.
- `npm config`: Gerencia as configurações do npm, como o registro padrão, proxy e cache.
- `npm pack`: Empacota o projeto em um arquivo tarball, útil para distribuição ou instalação em outro lugar.
- `npm ci`: Instala as dependências exatamente como estão definidas no `package-lock.json`, útil para ambientes de CI/CD ou builds determinísticos.
