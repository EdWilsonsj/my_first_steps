Enum:Após criado a sua conta no GitHub, crie um repositório remoto público chamado “my_first_steps” e cole o link aqui;
R1:https://github.com/EdWilsonsj/my_first_steps/
Enum2: Crie um diretório em sua máquina e o vincule ao seu repositório remoto “my_first_steps” utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.
R2:$ git init (criação do diretório)
$ git remote add origin https://github.com/EdWilsonsj/my_first_steps.git  (vinculando o diretório ao repositório remoto criado na questão 1)
Enum3: Dentro do diretório em sua máquina, crie um arquivo chamado “ola_mundo.txt”, adicione algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.
R3: $ vi ola_mundo.txt
$ git add ola_mundo.txt
$ git status 
$ git commit -m olamundo ex3 
$ git push -f origin main  (arquivo para o diretório remoto)
Enum4: Se não existir em seu diretório, adicione ao seu diretório um arquivo com o nome de “.gitignore”. Em seguida, crie um arquivo chamado “serei_ignorado.txt” e adicione algum texto dentro dele. Adicione a instrução ao arquivo “.gitignore” para que as alterações realizadas no arquivo “serei_ignorado.txt” não seja controlado pelo git. Cole aqui o conteúdo que você utilizou no “.gitignore” para realizar esta tarefa.

R4: $ vi serei_ignorado.txt (criando o arquivo de texto serei_ignorado.txt)
$ vi .gitignore       (dentro do arquivo gitignore, especificar o serei_ignorado.txt)
                                 serei_ignorado.txt > esc > :wq
$ git add .gitignore
$ git commit -m ex4
$ git status

