## Configurando sua identificação no Git

git config --global user.name "<span style="color:blue">Seu nome</span>"  
git config --global user.email "<span style="color:blue">Seu email de cadastro do Github</span>"git  
  
config --list  <small>(Ele exibe uma lista das configurações atuais ou disponíveis)</small>
  
##  Passo a passo: salvar primeira versão de um projeto no Github
  
  Considerando que agora seu ambiente já está todo configurado (usuário e email, visualização de
arquivos ocultos, chave SSH), sempre que você criar um novo projeto, os passos básicos serão
estes (troque os parâmetros em azul pelos seus dados):  
  
git init  
git add .  
git commit -m "Mensagem explicativa"  
git branch -M main  
git remote add origin git@github.com:seuusuario/seurepositorio.git  
git push -u origin main  

  
## Passo a passo: salvar uma nova versão
git status  
git add .  
git commit -m "Mensagem explicativa"  
git push  

