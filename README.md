# Meu-reposit-rio-beb-
## Primeiro passo de um bit mas um grande passo para o dev
Bomm, vou criar meu primeiro projeto!
# Algumas anotações sobre a introdução do git/github
# Introdução ao git e ao git Hub 
## 1- A importância dessa importância:
* Git
* Facilitador do dev
* Criado em 2005
* Ferramentas de versionamento de código.
* Software de colaboração.
* Git e git Hub são diferentes porém complementares
* Git Hub repositório de código
# Benefícios do github
* Controle de versao
* Armazenamento de nuvem
* Trabalho em equipe
* Melhorar seu código
* Reconhecimento
# Comandos básicos para um bom desempenho no terminal
* Git é por linha de comando e não gráfica
* ...O que vamos aprender
* ...
* Mudar de pastas
* Listar a pasta
* Criar as pastas e arquivos
* Deletar pastas e arquivos
##  Windows e unix
* Cd
* Dir.       Is
* Mkdir.             
* del/rmdir. rm-rf
## Dir lista os diretórios no windows e para o Linux é Ls
* Cd / permite que navega entre as pastas
* E pode intercalar com o Dir no caso windows ou ls no linix
* Cd.. retrocede
* Cls limpa a tela no windows
* Clean limpa a tela no linux
* Ou ctrl l limpa no linux
* O tab complementa a parte onde está
* Mkdir cria uma pasta
* A busca se dar por cs
* Para escrever algo numa pasta 
* C:\ workspace> echo hello
* Retorna o hello

* C:\ workspace> echo hello> hello.txt
* Cria um arquivo de texto na pasta workspace
* Para listar C:\workspace>dir
* O del deleta arquivos
* C:\> del workspace
* Mas dar erro 
* Workspace é um diretorio e somente deleta arquivos dentro
* Para deletar um diretorio
* Usa o rmdir
* C:\>rmdir workspace /S /Q
* Para o Linux -rm-rf
* Git clone clona o arquivo
* Resolvendo conflito.
*git clone faz o download do código do git Hub
# Cada programador faz do sei jeito , porém contém a edição na mesma linha 
## Aí não tem mais a mesma sicronia 
## Aí dar problema de junção 
## Aí o próprio programador tem que resolver
# Algoritmo de encriptação 
# Embaralha seu código 
## -A saída desses dados dera um conjunto de caracteres de 40 dígitos-Para poder identificar os arquivos de uma forma mais fácil 

* Para abrir o sha1 do arquivo 
* openssl sha1 texto.txt
* .......Objetos internos do git.....
* 1-.......Blobs .....
* 2-.......Trees ......
* 3-.......Commits..... 
## Blob tem o tipo, tamanho,a barra e o conteúdo -nao guarda o nome
### Trees armazenam os blobs-grau hierárquico ,guarda o nome 
*Podem aportar sobre blobs ou outras árvores -trees
* Commit
* Junta tudo
* E aponta para essas todas sub divisões 
* Tem um tempo de criação
* Possuem sha1
* Ele é único para cada pessoa.
# ..............Chaves SSH & tokens..........
* Chave ssh 🔑 
* Chave de segurança 
* Sequência 
* Ssh-keygen-t ed 25519 -c e-mail
* Gera duas chaves
* buscando a chave
* cd/c/Users/Nome/.ssh/
* ls
# Aí gera duas chaves
## Exemplo:
* id_ed25519 id_ed25519.pub
# Iniciar o ssh
### $ eval $(ssh-agent -s)
### $ ssh-add id_ed25519 

# Primeiros comandos com o git
* git init
* git add
* git commit 

# Criando um repositório 
* Git bash já adianta nosso trabalho 
* $ ls lista as pastas dentro do diretório 
## Aí já entra
* $ cd worspace/
* Já está dentro da pasta worspace 
* $medir livro-receita
## Entrando
* $ cd livro-receitas/
* Iniciando o git
* $git-init
*Inicializa um repositório git 
## $ ls não adianta nesse caso pois é oculto
* Para isso
* $ls -a
* Agora entrando na pasta git
* $ cd.git/
## Listando $ls
### Aí aparece
* Para voltar um comando lembrando 
* $ cd..
* Pronto!
* Git vai pedir um user name, email e senha
* $ git config--global user. email "email"
* $ git config -- global user.name gablops 

# Markdown
* Pasta.md
* Ver o que é Typora 
* COMMIT
* $ git add * 

* $ git commit -"commit inicial"


# Ciclo de vida dos arquivos 

* git init cria um repositório 
* Staged preparação de arquivos de comandos 
* Ultracked arquivos jovens que não temos ciência deles 
* Unmodified muda para modified se alteramos
* git status mostra o status do commit
* mv move o arquivo um repositório no outro
* $ mv arquivo.md ./ pasta/
* Para mudar os arquivos para staged fazemos: $ git add nome.md pasta/

