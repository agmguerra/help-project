# help-project
alguns comando uteis para diversos tipos de projetos. Para o caso de eu esquece :)

## adicionar um projeto ao github

1. Crie um repositório no GitHub. Para evitar erros, não inicialize o novo repositório com os arquivos LEIAME, de licença ou gitignore. É possível adicionar esses arquivos após push do projeto no GitHub.
2. Abra Git Basho terminal.
3. Altere o diretório de trabalho atual para seu projeto local.

4. Inicialize o diretório local como um repositório Git.
  <blockquote>
    $ git init
  </blockquote>
  
5. Adicione os arquivos ao novo repositório local. Isso faz stage deles para o primeiro commit.
  <blockquote>
  $ git add .
  </blockquote>

6. Faça commit dos arquivos com stage em seu repositório local.
  <blockquote>
  $ git commit -m "First commit"
  </blockquote>

7. No prompt de comando, adicione a URL para o repositório remote onde será feito push do seu repositório local.
  <code>
    $ git remote add origin remote repository URL
  
    Define o novo remote
    
    $ git remote -v
    
    Verifica a nova URL remota
    
  </code>
