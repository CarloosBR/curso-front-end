# Dicas do terminal

Vou listar alguns comandos que estamos aprendendo:

-   `cd` (navega entre pastas)

```
cd nomeDaPasta
```

Exemplo para sair de um pasta:

```
cd ..
```

-   `mkdir` (cria pastas)

```
mkdir nomeDaPasta
```

# Dicas do Git

-   `git init` (começa a seguir as pastas e arquivos de um projeto).

    -   Utilizmos esse comando para começar um projeto com o git. Chamamos a pasta do projeto de repositório(repo). Para utiliza-lo, é só entrar na pasta do projeto e executar o comando

-   `git status` (Informa o estado do repo).

    -   Exibe informações do estado dos arquivos e pastas. Exibe informações apenas dos arquivos e pastas novos, removidos ou alterados.

-   `git add`(segue os arquivos ou pastas no momento atual)Com o comando git status você fica sabendo do rolê dos arquivos e pastas e com o git add voce guarda esse momento dos arquivos e pastas para em seguida realizar o commit(commit??? Leia abaixo).

Se voce quer quardar o momento de todos os arquivos e pastas só executar o comando abaixo:

```
git add
```

-   Mas se voce quer pegar apenas alguns arquivos, voce pode deiar o comando mais especifico, dessa forma:

```
- `git add pasta/arquivo`
```

-   `git commit`(guarda momento atual) Com o `commit` não é mais necessário ficar criando past old ou com datas lokas. Ele é o cara que guarda o momento do seu repo. A parte legal é que voce deve e pode informar uma mensagem junto com o momento atual para ficar mais fácil de achar esse estado se precisar voltar até nele. Ex:

```
git commit - m "Anotações do git até o commit"
```

-   ´git log´(lista dos estados que guardamos `commit`) Com esse comando conseguimos ver todos os commits que já fizemos na vida do repo que voce estiver
