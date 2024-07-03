# teste-cast-lc
vai ser um site criado em conjunto, o objetivo é 
ganhar experiencia de trabalho em eqipe.

você vai instalar normalmente o git
depois que ele for instalado você pode fechar ele.

>crie uma nova pasta para o site
>dentro da pasta clique com o botao direito
em qualquer lugar em branco, em seguida clique
em open git bash.

>no git bash escreva "git init" sem aspas, e pressione
enter.

>agora vá na pagina do github 
https://github.com/Eztasy/teste-cast-lc

>clique no botão verde chamado "code"
>copie o link https aí em code.

>volte para o terminal do gitbash.

>use o comando "git clone (o link que você copiou aqui)"
sem aspas e sem parenteses.

esse comando vai clonar o arquivo na sua maquina, assim vai ter um na minha, na sua e um na pagina do github.

agora a ultima configuração que você vai fazer nessa parte é simples, você vai ligar o terminal do bash com o codigo do github.
só pra avisar pra ele que é pra la que você vai enviar as atualizaçoes e que é de lá que você vai puxar as atualizaçoes
usa o comando
git remote show origin
se já tiver um link aparecendo e o link for o mesmo da pagina do github significa que já ta tudo certinho
se não vc vai usar esse comando
$ git remote set-url --add origin https://github.com/Eztasy/teste-cast-lc


agora usa o comando
git config --global user.name "Lincoln" 
ou qualquer nick que você queira usar, é que assim vou saber que foi você que fez a alteraçao, meu usuario é Eztasy.

basicamente o git clona o diretório na sua maquina, usando o comando git init você cria um diretório que caso você faça algum erro da pra recuperar
pra versao anterior, o comando 
git add .
vai adicionar todas as alteraçoes que você fez na lista de salvamento, em seguida para salvar as alteraçoes você vai usar o comando
git commit -m"eu mudei a cor da parte de trás do site"
assim vai ficar salvo essa atualizaçao e a mensagem diz o que vc mudou nela. depois é só repetir a mesma coisa se precisar salvar outra atualização.

basicamente os comandos que você vai usar são
git pull
esse comando puxa as atualizaçoes que eu fiz, assim seu arquivo fica com minhas modificaçoes antes de vc começar a fazer o codigo, o git clone também funciona
mas esse é mais pratico, o git clone vai ficar clonando toda hora uma pasta no seu pc, esse só vai puxar as alteraçoes e é o jeito certo.

git push
a mesma coisa só que ao contrario, você vai enviar suas modificaçoes pro site do github e de lá eu vou poder usar o git pull pra
atualizar o meu codigo na proxima vez que for modificar
assim nós dois trabalhamos juntos sem quebrar o codigo um do outro.

qualquer erro ou duvida me chama no zap, ou pesquisa no google, é bem tranquilo de usar e eu passei tudo que vc precisa saber aqui, que tal deletar a pasta que ele
puxou e tentar de novo agr? vai usar o git clone, dps vc modifica algo no codigo ou cria uma nova pasta e da o comando 
git add .
depois git commit -m"exemplo, adicionei uma pasta com um arquivo txt"
e por fim
git push
para empurrar as alteraçoes..
pastas vazias não são identificadas, vc tem que adicionar algo dentro dela para ela ser considerada uma atualizaçao do codigo.
