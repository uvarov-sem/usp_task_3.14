# GIT help 

Прежде чем создать первый репозиторий, запустите команду git help. Он отображает полезную информацию о самом Git:

`$ git help`  
`usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]`    
>>>>>>>>>>>`[--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]`    
           `[-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]`  
           `[--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]`  

`...`


Мы также можем проверить руководство для конкретной команды несколькими способами:

`$ git --help init`  
`$ git help init`  
`$ git init --help`

Все три приведенных выше варианта возвращают одинаковый результат.

С опцией -g мы также можем получить доступ к списку внутренних руководств для развития наших навыков :

`$ git help -g`  
`The common Git guides are:`  
>>>`attributes          Defining attributes per path`  
`cli  Git command-line interface and conventions`      
`core-tutorial & A Git core tutorial for developers`  

`...`  
`$ git help core-tutorial`

Чтобы распечатать учебник, нам нужно указать его имя в качестве параметра.