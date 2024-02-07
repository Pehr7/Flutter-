! Add projeto Git Bash para o GitHub !


\\ Iniciar o git bash em uma pasta
git init 

Depois de iniciar na pasta pode mover ou criar um cod na pasta ref.
     (Sempre usar esse comando antes de enviar os arquivos)


\\ Verificar se a pasta esta atualizada 
git status 

O git status mostra quais pastas esta atualizada e quais precisa atualizar.
    (Sempre verficar se esta atualizado ou se tem algum arquivo pedente)


\\ Adicionando um arquivo 
git add "Nome_do_arquivo"

Git add com o nome do arquivo ou add para atualizar os arquivos que esta pendentes.
    (Verificar sempre os arquivos em vermelho para atualizar)


\\ Criar versões do codigo com Commit
git commit -m "Inicial" 

Commit sempre usar para quando for add uma veesão nova do projeto 
  (Manter sempre atualizado o commit pra facilitar o projeto)


 \\ Configurar email e user 
git config --global user.email "seu_email@exeplo.com"
git config --global user.name "Seu nome"

Add seu email e user para sincronizar com o GitHub
   (Manter o mesmo email e user do GitHub para migrção)


\\ Add link do GitHub 
git remote add origin https://github.com/seu_projeto

Add link para sincronizar os arquivos do Pc para o GitHub
  (Link do navegador dentro do seu repositorio para add)


\\ Subir arquivos para o GitHub
git push

Comando para subir os arquivos direto para o repositorio GitHub
 (Caso der erro usar o comando abaxio para confirmar a conta)


\\ Enviar arquivo para a master 
git push --set-upstream origin master

Add projeto direto para o repositorio GitHub
 (Na primeira vez vai solicitar a confirmação de conta)


\\ Verificando o historico
git reflog

Verificar os historico e as versões atualizadas
 (Sempre usar para verificar qual versões estao sendo utilizada)

\\ Voltar a versão 
git reset --hard id:da versão

Usar caso tiver mais de uma versão no projeto
 (Comant da pra usar pra volta para a nova ou antiga versão)


