# E aí, pessoal! 👋

### Eu sou Roberto Schneider <a href="https://www.linkedin.com/in/robertoschneider/"> <img src= "https://media2.giphy.com/media/tsUDdndB8zkFF8zHQM/giphy.gif?cid=ecf05e47bksdbsf1rkfjr2x53nf7r9t6q1ar4xguz4mkjqoa&rid=giphy.gif&ct=s" height ="40" width="40"/> </a>

- Estou trabalhando na TOTVS atualmente, com Python, SQL e Power BI
- Estou aprendendo Git e Github
- Pergunte-me sobre Python, Matemática e Ciência de Dados
- Como me encontrar: no <a href="https://www.linkedin.com/in/robertoschneider/" target="_blank">meu perfil no Linkedin</a> ou me mande um <a href="mailto:roberto.schneider@gmail.com?subject=Contato via Github">e-mail</a>
- Pode falar comigo nas minhas redes que você confere <a href="https://linktr.ee/betoschneider" target="_blank">https://linktr.ee/betoschneider</a>

### []s

# GIT: Comandos, links e tutoriais

## tutorial git Github
### primeiros passos (esse video me ajudou muito!)
* https://www.youtube.com/watch?v=UBAX-13g8OM
### git com arquivos binários (pbix e xlsx por exemplo)
* https://www.youtube.com/watch?v=6OokP-NE49k&t=1020s (minuto 24:48)
### acertando commits
* https://www.youtube.com/watch?v=6OokP-NE49k&t=1020s (minuto 3:10)

## Links úteis:
### Configurar acesso bash Github
* https://blog.cod3r.com.br/autenticacao-no-github-pela-linha-de-comando/
* https://www.alura.com.br/artigos/nova-exigencia-do-git-de-autenticacao-por-token-o-que-e-o-que-devo-fazer
* https://www.horadecodar.com.br/2022/02/17/como-remover-remote-origin-de-repositorio-em-git/
* https://stackoverflow.com/questions/19730565/how-to-remove-files-from-git-staging-area
* https://www.horadecodar.com.br/2021/10/26/como-desfazer-um-git-reset-no-repositorio/
* https://www.atlassian.com/br/git/tutorials/undoing-changes

## download do lfs
https://git-lfs.github.com/

## principais comandos
* verificar versão instalada: git --version
* iniciar git: git init
* alterar nome do branch: git branch -M "main"
* adicionar arquivo na stage: git add nome_do_arquivo
* remover arquivo da stage: git reset -- nome_do_arquivo
* remover todos os arquivos da stage: git reset --
* adicionar diferentes modificações de um arquivo em commits diferentes: git add -p (no menu, digitar s de split e depois y ou n para adicionar ou não no commit)
* verificar arquivos na stage: git status
* enviar arquivos: git commit -m "comentário do commit"
* empurrar arquivos para o respositório do Github: git push -u origin main
* puxar atualizações remotas: git pull
* sair do editor de mensagem commit pull: :qa!
* criar nova branch: git checkout -b "nova_branch"
* trocar de branch: git checkout branch_desejada
* merge entre as branch: checkout para a nova branch e depois executar: git merge branch_anterior
* binário lfs - iniciar lfs: git lfs install
* binário lfs - adicionar tipos de arquivos ao lfs: git lfs track "*.extensao"
* ver o pach completo de alterações: git diff
* retornar versões anteriores mantendo as alterações: git reset --soft HEAD~n
* retornar versões anteriores mantendo as alterações (no stage): git reset --soft HEAD~n
* retornar versões anteriores e apagar as alterações (CUIDADO): git reset --hard HEAD~n
* excluir um arquivo da pasta (repositório): git rm nome_do_arquivo e depois dar um commit
