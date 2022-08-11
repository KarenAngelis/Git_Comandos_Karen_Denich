1. Git clone
Git clone é uma comando para baixar o código-fonte existente de um repositório remoto (como, por exemplo, o Github). Em outras palavras, git clone, basicamente, faz uma cópia idêntica da versão mais recente de um projeto em um repositório e a salva em seu computador.

Há algumas maneiras de baixar o código-fonte, mas, em geral, eu prefiro a maneira de clonar com https:

git clone <https://link-com-o-nome-do-repositório>

2. Git branch
Branches (algo como ramificações, em português) são altamente importantes no mundo do git. Usando as branches, vários desenvolvedores conseguem trabalhar em paralelo no mesmo projeto simultaneamente. Podemos usar o comando git branch para criar, listar e excluir as branches.

Como criar uma branch:

git branch <nome-da-branch>

3. Git checkout
Esse também é um dos comandos do Git mais usados. Para trabalhar em uma branch, primeiro, é preciso "entrar" nela. Usamos git checkout, na maioria dos casos, para trocar de uma branch para outra. Também podemos usar o comando para fazer o checkout de arquivos e commits.

git checkout <nome-da-branch>