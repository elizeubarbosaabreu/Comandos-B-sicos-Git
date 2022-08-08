# Aprendizado GitHub

Aprendendo no site [dio.me](https://dio.me)

Professor: Venilton FalvoJr

Visualizar [Slide](https://drive.google.com/file/d/1IZu0qohv1JOmxjEra1lknDiiStU68bl4/view)

Baixar [Slide](https://github.com/elizeubarbosaabreu/aulagithub/raw/09da4ee99f8783482b34eb9c405ab5b1a6b01790/Apostila.pptx)
>> O importante é aprender de verdade, não aprender rápido! (pensamento meu mesmo, rsrs)
## Comandos Básicos do Git

- comando para clonar um repositório:
~~~
git clone git@github.com:usuario/repositorio.git
~~~
- comando para inicializar o git em um repositório local:
~~~
git init
~~~
- comando verificar status um repositório:
~~~
git status
~~~
- status resumido:
~~~
git status -s
~~~
- comando para adicionar um arquivo para o repositório local:
~~~
git add nomedoarquivo
~~~
- comitar um arquivo:
~~~
git commit -m "<resumo das alterações>"
~~~
- comando para empurrar um repositório:
~~~
git push
~~~
- atualizar repositório com conteúdo remoto:
~~~
git pull
~~~
- fazer merge
~~~
git merge <branch>
~~~
- corrigir erro em arquivo local de acordo como remoto:
~~~
git checkout -- <arquivo>
~~~
- remover todas as alterações locais e deixar tudo igual ao repositório remoto:
~~~
git fetch origin
git reset --hard origin/master
~~~

## Outras configurações

- Deixar o terminal do git colorido:
~~~
git config color.ui true
~~~
