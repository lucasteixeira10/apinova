# Documentação

 

Criar a pasta

```

mkdir projetoBackend

```

Acessar pasta

```

cd projetoBackend

```

Criar arquivo para documentar o projeto

```

touch readme.md

```

Iniciar o gerenciador de pacotes Node

```

npm init -y

```

Instalar os pacotes

```

npm i express nodemon dotenv

```

Abrir o VSCode

```

code .

```

Criar arquivo .gitignore

```

nano .gitignore

```

Adicionar no arquivo .gitignore o nome da pasta criada após a instalação dos pacotes

```

node_modules

```

Criar estrutura de arquivos e pastas

```

mkdir src

```

Criar arquivos dentro das pastas src

```

touch src/app.js

```

Arquivo responsável de criar a configuração da API

```

touch src/server.js

```

Criar pastas dentro da pasta src

```

mkdir src/config

```

Pasta para gerenciar a conexão com banco de dados

```

mkdir src/controllers

```

Pasta para gerenciar as requisições das rotas e conexão com banco de dados

```

mkdir src/routes

```

Enviar estrutura do projeto para o github: nicializar o gerenciador de arquivos .git

```

git init

```

Informar nome

```

git config --global user.name "FIRST_NAME"

```

Informar email

```

 git config --global user.email "EMAIL@EXAMPLE.COM"

```

 Verificar arquivos que serão enviados ao gitHub

 ```

 git status

 ```

 Adicionar todos arquivos ao versionamento

 ```

 git add .

 ```

 Salvar projeto e escrever comentário sobre o processo realizado

 ```

 git commit -m 'estrutura do projeto'

 ```

 De volta ao terminal, executar o comando para definir a branch main

 ```

 git branch -M main

 ```

 Colar a URL do seu repositório copiada

 ```

 git remote add origin COLAR_URL

 ```

 Enviar os arquivos para o gitHub

```

git push -u origin main

```

Com o projeto no servidor remoto podemos remover os arquivos na nossa máquina

```

cd ..

```

Fechar o VSCode com o projeto aberto

```

rm -rf projetoBackend

```
