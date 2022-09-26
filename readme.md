Estudando Git!

Clicar com botão direito do mouse no diretório:

1. Abrir com Code;
2. Git Bash here;

git --version
Verifica a versão do git;

git init
Inicializa um repositório git vazio;

<!-- master = branch master = main -->

git add nomeDoArquivoQuePretendeMandarParaEssaÁrea  
Comando que manda os arquivos para a área de staging.

git status
Informa o status do git, se há mudanças a serem commitadas, por exemplo.

git commit -m "comentário/mensagem"
Commita o arquivo (commits são versões do arquivo).

git branch -M "main"
O git tem mudado a nomenclatura da branch principal, de "master" para "main";
portanto, para modificar a nomenclatura, usar o comando acima.

git remote add origin https://github.com/monicaquintal/EstudandoGit.git

<!-- para colar no Git, usar ctrl + shift + V ou Insert> -->

Cria conexão entre repositório local (pc) e o GitHub.

git push -u origin main
Envia um arquivo para o GutHub;
"push" quer dizer, literalmente, empurrar os commits do repósitório local (Git) para o repositório remoto (GitHub);

teste

TESTANDO COM O TOKEN

  TOKEN GERADO, COMMIT PELO TERMINAL FEITO COM SUCESSO
  
  teste