# GIT

Git nada mais é um sistema de versionamento de arquivos, onde podemos desenvolver projetos e qualquer pessoa pode contribuir nele simultaneamente, editando e criando novos arquivos. 

O Git tem algumas formas se segurança e uma delas que me chamou mais atenção foi o SHA1, que é um sistema de segurança que embaralha seu arquivo, código, foto, texto... em 40 dígitos únicos, bem parecido com a criptografia que conhecemos e está presente nas redes sociais que usamos quase todos os dias.

Sobre os objetos internos do Git, é muito interessante como cada objeto, tanto o commit, tree e os blobs tem seu próprio SHA1 e quando faz uma modificação em um blob, muda o SHA1 de todos os objetos.  E cada alteração que fez tem o seu SHA1 e essas alterações ficam na nuvem guardada para quando quiser sempre consultar, sabe?

Os objetos internos são organizados por hierarquia, os blobs ficam dentro da tree e a tree fica dentro do commit. Vou deixar uma imagem bem legal para terem uma noção de como funciona essa organização. 

![image](https://user-images.githubusercontent.com/109253392/179214130-b16f04d4-62ad-4021-a397-ea9e18d5493c.png)

## Comandos

Agora vou mostrar alguns comandos básicos do Git para ter o melhor aproveitamento do software.

   Função | Windows| Linux
    ---------|----------|----------
    Criar uma pasta | `mkdir` | `mkdir`
    Listar uma pasta | `dir` | `ls` 
    Limpar o terminal | `cls` | `clear` ou `ctrl + l`
    Localizar arquivos| `cd /` | `cd /`
    Sair da pasta que está| `cd ..` | `cd ..`
    Excluir toda a pasta | `del` ou `rmdir`  | `rm - rf`
    Criar um novo repositório| `git init` | `git init`
    Clonar um repositório no terminal| `git clone` | `git clone`
    Confirmar as alterações e gerar um commit | `git commit` | `git commit`
    Mostra a lista de alterações naquele arquivo | `git status` | `git status`
    Envia suas alterações para o repositório main | `git push` | `git push`
    Adiciona o arquivo para o diretório local | `git add` | `git add`

Espero que tenham gostado, fiz esse projeto com todo amor e carinho, de forms simples para que realmente entendam como funciona um pouquinho sobre o Git, abaixo vou deixar o link de download do Git.
[Clique aqui para baixar](https://git-scm.com/downloads)
