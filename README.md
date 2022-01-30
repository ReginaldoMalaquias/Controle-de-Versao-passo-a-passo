# Controle-de-Versao-passo-a-passo
Meu passo a passo para criar controle de versão no Git e Github

Para criar o controle de versão no Git/GitHub
Realizei essa tarefa executando o seguinte passo a passo:


1) Criar a pasta no computador local com o nome do projeto
2) Acessa a pasta pelo GitBash
3) Inicializa o git > git init
4) Realiza as configurações global iniciais com nome e email da pessoas
5) Adicionar no git > git add *
6) Confirmar mudanças > git commit -m “descrição”
7) adiciona sincronismo do repositorio local para o repositorio remoto > git remote add origin https://github.com/ReginaldoMalaquias/exercicios-basicos-html.git
8) verificar se o repositório local está sincronizado com o remoto > git remote -v
9) empurra o repositório local para o repositório remoto > git push origin master


<p>
Chave SSH (SSH Key) é uma Forma de estabelecer uma conexão segura e encriptada entre duas máquinas por meio de chave publica e chave privada, uma forma de assinatura digital entre dois computadores.
1) Abre o Gitbash
2) ssh-keygen -t ed25519 -C xzy@gmail.com // gerando par de chave ssh publica e privada com base no e-mail cadastrado no gitbash, o mesmo que está no github
3) cd /c/Users/nomeuser/.ssh/ //acessa a pasta com as chaves
4) ls listas arquivos
5) cat id_ed25519.pub
6) vai mostra o conteudo da chave publica, copiar esse conteudo
7) adiciona o conteudo da chave no github em new ss key
8) no Gitbash lista a chave com o comando ls
9) comando eval $(ssh-agent -s) // inicia o projeto
10) ssh-add id_ed25519 // dentro da pasta onde estao as chaves, adiciona a chave privada
11) informa a senha cadastrada no inicio desses passos
12) git clone [endereco ssh] //pega o endereco ssh para clonar repositorio github
13) digite yes, caso pergunte algo
14) pronto, repositorio clonado
</p>




<p>
1) Acessa o diretorio por linha de comando, no gitbash por exemplo
2) git init // inicializar o repositorio 
3) ls -a // mostra as pastas ocultas
4) cd .. //volta um nivel
5) git config --global user.email "meuemail@gmail.com"
6) git config --global user.name Fulano
7) // markdown é uma forma mais humana de escreve arquivo html


</p>



