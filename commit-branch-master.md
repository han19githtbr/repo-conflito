echo "#commit-2-branch-master" > commit-2-branch-master.md --> cria um arquivo chamado commit-2-branch-master.md e escreve #commit-2-branch-master dentro dele

criar uma nova branch: git checkout -b teste

git branch -v : mostra o último commit de cada branch

git branch : lista todas as branchs

Se quisermos que as alterações que fizemos lá na branch teste apareçam na nossa branch master, devemos mesclar as branchs (git merge nomedabranch)

git branch -d nomedabranch : para excluir uma branch
