# UltiSnips snippets

Steps:

1. clone repo

        git clone https://github.com/chan-grammer/myUltiSnippetsCollection.git ~/.vim/mySnippets

2. make modifications to vimrc

        let g:UltiSnipsSnippetDirectories=["UltiSnips", "mySnippets"]
        " what folder to store snippets when invoking :UltiSnipsEdit
        let g:UltiSnipsSnippetsDir="~/.vim/mySnippets/"
