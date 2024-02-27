// // // // // //// O INICIANDO  // //// // //// // //

Projeto que ensina a usar o Github

==> cd _Diretorio_ (seleciona o diretorio do que será feito)

==> mkdir _Diretorio_ (Em caso de conflito com a pasta)

==> git init (inicializa o repositorio vazio) 

(Master. Branch principal criada automáticamente)

.git é uma pasta criada automáticamente para suas proprias usualidades. 

// // // // // //// // GIT ADD // //// // //// // //// // //


==> git add _nomeFile_ (Manda os arquivos para areas de stading ("chama dos fundos para ser empurrado para o palco (commit)")). 
==> git add . (adiciona todos os arquivos para stading)

Ex: git add Readme.md (adicionar o arquivo)


==> git status 



// // // // // ////  NOMECLATURA MASTER PARA MAIN  // //// // //// // //



==> git branch -M "main" (Muda para main, apenas questões visuais.)


// // // // // ////  GIT COMMIT  // //// // //// // //

==> git commit -m "_nome do Commit_"  (Aqui já criamos o repositorio local e damos o commit para o github)


// // // // // //// INDO AO GITHUB  // //// // //// // //

Crie um repositorio com o mesmo nome da pasta 


==> git remote add origin _linkrepositorio_ (linkado uma única vez)

(remote, coneção / add para adicionar / origin para o nome no github / link)



==> git push -u origin main


// // // // // //// PUSH APÓS PRIMEIRO PUSH  // //// // //// // //

==> git push origin main (Não precisa mais do -u)

// // // // // //// // Criando a  BRANCH // //// // //// // //// // //

git checkout -b "_Nome_" (criamos uma nova branch) 

com isso saímos da principal que estavamos (main/master) para a nova branch criada (_Nome_)


