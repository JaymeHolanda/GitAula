// // // // // //// // AULAS DE GIT BRANCH // //// // //// // //// // //

Conceito: Uma branch é como um "caminho paralelo". Imagine o código como uma estrada principal. Uma branch permite que você crie uma nova estrada a partir da principal, para testar novas ideias ou corrigir erros sem afetar o código original.

/// VANTAGENS /// 

// Permite testar e desenvolver novas ideias sem afetar o código principal.
// Facilita o trabalho em equipe, pois cada desenvolvedor pode trabalhar em sua própria branch.
// Ajuda a manter o código organizado e fácil de entender.



// // // // // //// // Criando a BRANCH // //// // //// // //// // //

==> git checkout -b "_Nome_" (criamos uma nova branch) 

com isso saímos da principal que estavamos (main/master) para a nova branch criada (_Nome_)


// // // // // //// // VOLTANDO PARA A BRANCH MAIN // //// // //// // //// // //

==> git checkout main


// // // // // //// // JUNTANDO BRANCHS (MERGE) // //// // //// // //// // //

PRECISA SER NA MAIN 

git checkout main 

==> git merge _nomeDaBranch_ (isso junta a princial (que você já se encontra, com a Branch que você quer da merge.))