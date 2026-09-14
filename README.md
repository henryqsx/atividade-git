1. mkdir atividade-git
Cria uma pasta chamada atividade-git.

2. cd atividade-git
Entra na pasta criada.

3. git init
Inicializa um repositório Git dentro da pasta.

4. git branch -M main
Renomeia a branch principal para main.

5. touch index.html
Cria o arquivo index.html.

6. echo "<h1>Minha atividade Git</h1>" > index.html
Adiciona um título ao arquivo HTML.

7. git add index.html
Adiciona o arquivo para ser salvo no próximo commit.

8. git status
Mostra o estado atual dos arquivos no Git.

9. git commit -m "Primeiro commit"
Salva a primeira versão do projeto no histórico do Git.

10. git switch -c develop
Cria a branch develop e muda para ela.

11. git branch
Mostra as branches existentes.

12. echo "<p>Henry Oliveira</p>" >> index.html
Adiciona um novo parágrafo ao arquivo HTML.

13. git add index.html
Prepara a alteração para o próximo commit.

14. git commit -m "Altera index.html"
Salva a alteração feita na branch develop.

15. git log --oneline
Mostra o histórico dos commits de forma resumida.

16. git remote add origin https://github.com/henryqsx/atividade-git
Conecta o projeto local ao repositório do GitHub.

17. git push -u origin develop
Envia a branch develop e seus commits para o GitHub.
