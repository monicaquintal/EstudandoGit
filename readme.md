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
<br>

<h2>git clone link.git</h2>
<p>Para clonar um Repositório, clicar no botão "Code", e copiar o link;<br>
Criar uma nova pasta no pc, entrar nela e inserir o comando "git clone 'link'.git" no GIT Bash/VS Code;<br>
O comando <em><strong></em>cd</strong> permite entrar em outros Repositórios.<br>
</p>
<br>

<h2>git pull</h2>
<p>Atualiza a versão que possímos do arquivo no pc ("puxa" a versão mais atualizada de um Repositório, com as últimas alterações feitas.</p>

<hr>

<h2>Fork</h2>
<p>O git clone puxa os arquivos para a máquina; se quiser que eles constem no github, clicar no botão "Fork" (indica a origem do Repositório, e importa pra sua conta).</p>
<br>

<h2>Pull request</h2>
<p>É uma solicitação para que aceitemos alterações em nosso projeto, feitas por outra pessoa;<br>
Para tal, commitar as alterações no próprio perfil, clicar em "Contribute", e em "Open pull request";<br>
Colocar um nome objetivo, que demonstre a funcionalidade incluída, além de descrever o que desenvolveu, e ensinando a forma de testar;<br>
Para aceitar o Merge, clicar em "Merge pull request".</p>