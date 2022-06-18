
# Primeiro repositório do curso de Git e GitHub.

Primeiramente

## O que é GiT?

O git foi criado por linus Torvalds após tentar ultilizar várias ferramentas de versionamento.
O seu objetivo era criar uma ferramenta open source capaz de gerenciar as milhares de contribuições 
de código no Kernel do Linus de forma eficiente.


como ele funciona na pratica

temos um repositório de código (pode estar local ou remoto)


para começar você precisa fazer um clone do seu projeto
para começar a desenvolver melhorias, funções e adiciona dentro de um commit
depois você envia todos os pacotes para um repositório  ultilizando o push.

Vamos começar!
```shell
Primeria etapa:
Instale o git e crie uma conta no GitHub
```
```shell
Segunda etapa:
Crie um repositório git local
```
![image](https://user-images.githubusercontent.com/107520340/174452987-a4676f0f-f3b4-4bad-b03c-cd29b218f47d.png)
abra o seu terminal e localize a pasta desejada

W+R > CMD

```shell
C:\Users\Jessi>cd/
C:\>cd projeto/
C:\Projeto>
```
Para inicializar um repositório na pasta raiz ,  utilize o comando : giti init
```shell
C:\Projeto>git init
Initialized empty Git repository in C:/Projeto/.git/
C:\Projeto>
```
```shell
Terceira etapa:
Adicione um arquivo ao seu repositório, vamos criar um arquivo txt como exemplo
```
![image](https://user-images.githubusercontent.com/107520340/174455645-7b47cd0e-5586-41d3-a099-f0b2cebd2f57.png)


depois você pode dar o comandos: git status

```shell
C:\Projeto>git status
On branch main
No commits yet
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        GitHub
nothing added to commit but untracked files present (use "git add" to track)
```
podemos observar que estamos "untracked" é o estado onde o arquivo ainda não foi 'rastreado'
como podemos obsevar nessa imagem

![chrome_AefpVRZB4O](https://user-images.githubusercontent.com/107520340/174455192-73baf4e0-d85f-41cb-b186-d383c455dc92.png)

```shell
Quarta etapa:
adicinonar um arquivo ultilizando o comando: git add <file>
e depois o comoando: git status 
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   GitHub.txt      
```
podemos observar que mudou o status para "Unstage"

```shell
Quinta estapa:
Vamos criar o primerio Commit
comando: git commit -m "seu comentario"


C:\Projeto>git commit -m "Teste"
[main (root-commit) 8319196] Teste
 1 file changed, 1 insertion(+)
 create mode 100644 GitHub.txt
```
Pronto, já foi exportado o arquivo para o seu GitHub.

          nothing to commit, working tree clean
          
 
 

