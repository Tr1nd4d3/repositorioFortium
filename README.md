…or create a new repository on the command line
echo "# repositorioFortium" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Tr1nd4d3/repositorioFortium.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin https://github.com/Tr1nd4d3/repositorioFortium.git
git push -u origin master

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

git clone --> copiar da Master para o repositorio local
git status --> Verifica sua ultima atualização do repositorio
git pull --> atualiza o seu repositorio com a ultima versao da "Master"
