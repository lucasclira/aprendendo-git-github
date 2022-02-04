# Desafio sobre Git/GitHub da DIO e GFT Start
Desafio de Projeto sobre Git/Github

# Comandos práticos para uso do Git/GitHub.

### Link da documentação oficial: <https://git-scm.com/docs> 
### Link do livro ProGit: <https://git-scm.com/book>

&nbsp;

##### Iniciando um Repositorio
Comando | Ação
--------- | ------
 git init  | Inicializa o sistema de versionamento na pasta
 ---
 
##### Colaborando em um projeto descentralizado
Comando | Ação
--------- | ------
git clone _url-de-um-projeto_| Clona um projeto do GitHub
---

##### Configurando Credenciais
Comando | Ação
--------- | ------
git config user.name _nome_ | Muda/configura as credenciais de nome
git config user.email _e-mail_ | Muda/configura a credencial do e-mail
git config --list | Lista as configurações de credenciais 

* Obs.:nickname e email tem que ser iguais as credencias do GitHub.
---

##### Adiciona arquivos para versionamento

Comando | Ação
--------- | ------
git add _nome-do-arquivo_| Adiciona o arquivo para a stage
git add -a | Adiciona todos os arquivos para a stage
---

##### Comentando modificações
Comando | Ação
--------- | ------
git commit -m _"descrição"_| Realiza um commit com uma mensagem
---

##### Revertendo commits
Comando | Ação
--------- | ------
git reset _referencia-sha1_ | Volta commits até a referência indicada
git reset HEAD~1 | Volta um commit atrás
git reset --soft HEAD~1 | Desfaz o último commit e volta para stage 
git reset --mixed HEAD~1 | Desfaz o commit e volta para untracked
git reset --hard HEAD~1 | Desfaz o último commit e o exclui
git reset --revert HEAD~1 | Reverte um commit gerando um novo commit
---

##### Observando a árvore de trabalho
Comando | Ação
--------- | ------
git status | Exibe todas situações dos arquivos na área de trabalho
---

##### Observando registros de commits

Comando | Ação
--------- | ------
git log | Mostra os logs de commits
git log --stat | Mostra estatisticas de commits
git log --oneline | Mostra commits em uma linha
---

##### Vendo diferenças entre arquivos

Comando | Ação
--------- | ------
git diff _arq1_ _arq2_ | Mostra as mudanças entre commits, commit e árvore de trabalho
---

##### Trabalhando com branches(ramos)

Comando | Ação
--------- | ------
git branch -m| Move ou renomeia uma branch
git branch -d| Deleta uma brach
git merge _nome-da-branch_ | Incorpora as alterações entre branches
git checkout | Troca/restauração de branches
git checkout -b _nome-da-branch_ | Cria uma nova branch
---

##### Trabalhando com repositórios remotos

Comando | Ação
--------- | ------
git remote | Gerencia um conjunto de repositórios remotos
git remote add _nome-do-repo_ _url-do-repositorio-externo_ | Adiciona um repositório remoto
git push _nome-do-repo_ main  | Leva modificações locais para o repositório remoto
git pull _nome-do-repo_ main | Trás repositorio remoto para a máquina local



