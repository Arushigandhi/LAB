# LABS
MIT IT Lab Repository

To obtain **partial clone** of this repository, use the following commands:

    $ git init  
    $ git remote add origin -f https://github.com/Fabhi/LAB.git  
    $ git config core.sparseCheckout true #enable this  
    $ echo "Folder Name" >> .git/info/sparse-checkout 
    $ git read-tree -mu HEAD

For example, **to obtain only '4th Sem'**, use the following commands:  

    $ git init    
    $ git remote add origin -f https://github.com/Fabhi/LAB.git  
    $ git config core.sparseCheckout true  	
    $ echo "4th Sem" >> .git/info/sparse-checkout  
    $ git read-tree -mu HEAD

To report any erros, drop a pull request.

[![Run on Repl.it](https://repl.it/badge/github/Fabhi/LAB)](https://repl.it/github/Fabhi/LAB)
