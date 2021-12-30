# Comandos git
## git reset
retorna um commit
git reset [--soft, --mixed, --hard] <idcommit>
desfazer merger
git reset HEAD~1 
### git merge sem comitar
git merge master f1 --squash
### git merge comitando
git merge master f1

### git rebase
faz o mesmo que merge, porem junta o conteudo de um diretamnte na outra (cuidado em usar)
git chekout master
git rebase outrabranch
 ### editando mensagem do commit
 git commit -m 'message' --amend
 
 ### revertando brach remota para o commmit desejado
 git push -f origin <hashcommit>:branch 

 ### deletando brach remota
 git push origin :fix/authentication