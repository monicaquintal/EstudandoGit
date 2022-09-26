<h1>Estudando Git!</h1>

Clicar com botão direito do mouse no diretório:

1. Abrir com Code;
2. Git Bash here;

<hr>

<h2>git --version</h2>
<p>Verifica a versão do git.</p>
<br>

<h2>git init</h2>
<p>Inicializa um repositório git vazio; <br>
master = branch master = main.</p>
<br>

<h2>git add nomeDoArquivoQuePretendeMandarParaEssaÁrea</h2>  
<p>Comando que manda os arquivos para a área de staging; <br>
o comando <strong>"git add ."</strong> manda todos os arquivos para a área de stading!</p>
<br>

<h2>git status</h2>
<p>Informa o status do git, se há mudanças a serem commitadas, por exemplo.</p>
<br>

<h2>git commit -m "comentário/mensagem"</h2>
<p>Commita o arquivo (commits são versões do arquivo).</p>
<br>

<h2>git branch -M "main"</h2>
<p>O git tem mudado a nomenclatura da branch principal, de "master" para "main"; <br>
Portanto, para modificar a nomenclatura, usar o comando acima.</p>
<br>

<h2>git remote add origin https://github.com/monicaquintal/EstudandoGit.git</h2>
<p>Cria conexão entre repositório local (pc) e o GitHub;<br>
Para colar no Git, usar ctrl + shift + V ou Insert;<br>
Só é utilizado uma vez - a conexão com github só é feita uma vez.</p>
<br>

<h2>git push -u origin main</h2>
<p>Envia um arquivo para o GutHub;<br>
"push" quer dizer, literalmente, empurrar os commits do repósitório local (Git) para o repositório remoto (GitHub);<br>
O "-u" é utilizado apenas na primeira vez.</p>
<br>

<h2>clear</h2>
<p>Limpa a tela de comandos.</p>
<br>

<h2>git checkout -b "nomeDaBranch"</h2>
<p>Cria uma <strong><em>branch</strong></em>, que é uma ramificação do projeto (normalmente utilizada para desenvolver features);<br>
O nome entre aspas define o nome da nova branch, e o "checkout" indica a saída da branch main;<br>
Não necessariamente são adicionados novos arquivos, pode apenas modificar os já existentes;<br>
Utiliza os demais comandos normalmente: "git add .", "git commit -m 'nomeCommit'", "git push origin nomeDaBranch";<br>
E para voltar à main, utilizar o comando "git checkout main". </p>
<br>

<h2>git merge nomeDaBranch</h2>
<p>O <em><strong>Merge</em></strong> faz a junção da branch com a main;<br>
Para isso, usar os comandos "git checkout main", e "git merge nomeDaBranch".<br>
</p>