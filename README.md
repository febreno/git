#### ABOUT
- PR (pull request)
- hotfix (fix fast an bug)

#### CUMMON
```
git checkout -b feature/teste
git pull origin development
git add .
npm run dev
npm run build
```

#### SSH
````
git config --global user.name "febreno" 
git config --global user.email "test@gmail.com" 
git config --list
ssh-keygen
cat .ssh/id_rsa.pub
cd desktop
cd ~
ls -h
ls -a
cat .ssh/id_rsa.pub
cd .ssh
open .
(after: paste to github the new ssh)
````

#### git bash
```
git reset --hard (reset alterations)
git init (inicializar o rep)
git branch (ver branchs)
git branch -r (remotes)
git branch -a (all)
git fetch -vp (atualizar branchs)
git checkout origin/master
git reset --hard (back to last version)
git checkout -b (criar branch)
git checkout -b feature/EndpointHistoricoViagens
git push -d nomeBranch (deletar branch local)
git push --delete nomeBranch (deletar branch remota)
git push -u origin nome (dar o push na branch )
git push -u origin nomebranch (subir uma branch)
git push -f (sobrescreve) usado no community
git push --set-upstream origin namebranch (first push in branch)
git pull (puxar atualizacoes)
git pull origin development (puxar atualizacoes branch development)
git checkout nameBranch (entrar na branch) ex: CW-569
git checkout feature/retorna-historico-viagens
git remote set-url origin "url.clone"
git merge [branch] --allow-unrelated-histories
```
#### Passar para um novo repositório
```
git remote set-url origin "url.clone"
```

git remote set-url origin https://github.com/Control361/control361-front.git

```
git add .
git commit -m 'test'
git push

git pull origin development
```

#### VOLTAR PARA ÚLTIMO COMMIT
```
git reset --hard
```

#### PUXAR ATUALIZACOES SEM DESFAZER A ATUAL
```
git stash -u // -u quando tem arquivos novos
git pull
git stash apply
```

---
# infoGIT

GitHub is a web site that you can (see files in cloud)                                                                                                                       
- create account: https://github.com/                                                                                                                                           
 
Git is an  apk that for save to (the cloud > pc / pc > cloud)                                                                                                                               
- install: https://git-scm.com/downloads
---                                                                                                                                        
### Commands
1. git clone https://urlrepository

2. git add .
3. git commit -m "example"
4. git push
                                                                                                                                                                                 
---                                                                                                                                                                                                             
### clona um projeto (nuvem > pc)
  <img src="./img/gitclone.PNG" width="350" title="hover text">
  <img src="./img/gitBash.png" width="350" title="hover text">
git clone http://urlrepository

### adiciona atualizacoes(pc > nuvem)
- git add . (iniciar git)
- git commit -m "txt" (comentario)
- git push (subir para gitHub)

#### cometar sobre atualizacao
```
git commit -m "atualizado"
```
#### apenas salva (pc > nuvem)
```
git push 
ou
git push origin/master
```
#### atualizar um projeto ja salvo (nuvem > pc)
git pull
```

#### tenho 2 branchs e desejo passar as alteraçoes de uma para a outra, removendo tudo de diferente da outra

```
git checkout main (acessar a branch que receberá as alteraçoes)
git fetch origin
git reset --hard origin/development
git add .
git commit -m "merge"
git push
```
                                                                                                                                                                            
