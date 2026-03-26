# ARC-JOAO-RIBEIRO2
Nome:João Gabriel Ribeiro 
Nome:Felype Macario 
**Atividade semana 6**

Guia Básico de Comandos Linux (Bash) 

Atividade de Gerenciamento de Sistema Linux 

Durante esta atividade, utilizei diversos comandos no terminal do Linux com o objetivo 
de relembrar e aprender funções importantes para administração do sistema, 
manipulação de arquivos, gerenciamento de usuários e configuração de rede 
(complementei com IA pra ficar mais bonito e fácil de entender, mais foram todos 
testados e aprendi a função de cada um). 

Navegação e Listagem de Arquivos 

**ls** 
Lista arquivos e diretórios do local atual. 

Exemplo: 
ls 

**ls -l**
Mostra arquivos com detalhes (permissões, tamanho, data, dono). 

Exemplo: 
ls -l 

**ls -a**
Mostra todos os arquivos, inclusive ocultos.

Exemplo: 
ls -a 

**cd**
Entra em um diretório. 

Exemplo: 
cd nome_da_pasta 

**cd ..** 
Volta um nível no diretório. 

Exemplo: 
cd .. 

**cd -**
Volta para o diretório anterior acessado. 

Exemplo: 
cd - 

Manipulação de Diretórios 

**mkdir** 
Cria um novo diretório. 

Exemplo: 
mkdir teste 

Permissões e Usuários 

**sudo** 
Executa comandos com privilégio de administrador. 

Exemplo: 
sudo apt update 

**su**
Troca para outro usuário (geralmente root). 

Exemplo: 
su 

Gerenciamento do Sistema 

**systemctl** 
Gerencia serviços do sistema. 

Exemplo: 
systemctl status ssh 

systemctl start ssh 

systemctl stop ssh 

Gerenciamento de Pacotes 

**apt update** 
Atualiza a lista de pacotes disponíveis. 

Exemplo: 
sudo apt update 

**apt install** [pacote] 
Instala programas no sistema. 

Exemplo: 
sudo apt install net-tools 

Rede 

**ip address** (ip a) 
Mostra os endereços de rede da máquina. 

Exemplo: 
ip a 

**nslookup** 
Consulta o IP de um site via DNS. 

Exemplo: 
nslookup google.com

Gerenciamento de Usuários 

**adduser** 
Cria um novo usuário. 

Exemplo: 
sudo adduser usuario_teste 

**passwd** 
Altera a senha de um usuário. 

Exemplo: 
passwd usuario_teste 
 
