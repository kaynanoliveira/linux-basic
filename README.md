## 🖥️ Comandos Básicos

```sh
ls      # Lista os arquivos e diretórios
pwd     # Mostra o diretório atual
cd      # Navega entre diretórios
mkdir   # Cria um novo diretório
rmdir   # Remove diretórios
rm      # Remove arquivos
cp      # Copia arquivos ou diretórios
mv      # Move ou renomeia arquivos e diretórios
cat     # Exibe o conteúdo de um arquivo
clear   # Limpa o terminal
--help  # Pede ajuda 
history # Lista todos os comandos utilizados pelo usuário
!n      # Executa o comando de número n no histórico. Exemplo: !23
!!      # Executa o último comando digitado
./arquivo.sh  # Executa arquivo script 
```

## 📂 Gerenciamento de Arquivos

```sh
touch arquivo      # Cria um novo arquivo
nano               # Abre um arquivo no editor nano
vi                 # Abre um arquivo no editor vi
rm -r diretório    # Remove diretórios e seus conteúdos
find /caminho -name "*.txt"  # Encontra arquivos por nome
locate arquivo     # Localiza um arquivo no sistema
df -h              # Mostra o uso do disco
du -sh diretório   # Mostra o tamanho de um diretório
```

## 🔧 Permissões e Proprietários

```sh
chmod 755 arquivo        # Altera as permissões de um arquivo
chown dono:grupo arquivo  # Altera o proprietário de um arquivo
ls -l                    # Lista arquivos com permissões detalhadas
```

## 📌 Processos e Recursos do Sistema

```sh
ps aux          # Lista todos os processos em execução
top             # Exibe o uso dos recursos do sistema
kill PID        # Finaliza um processo pelo ID
killall nome    # Finaliza todos os processos com um nome específico
htop            # Versão avançada do 'top' (pode precisar ser instalado)
```

## 📡 Rede e Conexões

```sh
ifconfig           # Exibe informações da interface de rede (obsoleto, use 'ip a')
ip a               # Mostra os endereços IP das interfaces de rede
ping host          # Testa a conectividade com um servidor
wget url           # Baixa arquivos da web
curl url           # Faz requisições HTTP
netstat -tulnp     # Mostra portas abertas e conexões ativas
```

## 📦 Gerenciamento de Pacotes (APT - Debian/Ubuntu)

```sh
sudo apt update              # Atualiza a lista de pacotes disponíveis
sudo apt upgrade             # Atualiza todos os pacotes instalados
sudo apt install pacote      # Instala um pacote
sudo apt remove pacote       # Remove um pacote
sudo apt autoremove          # Remove pacotes desnecessários
```

## 🛠️ Usuários e Grupos

```sh
su             # Troca para o usuário root
su user        # Troca para um usuário específico
whoami         # Mostra o usuário atual
id             # Mostra detalhes do usuário
useradd user   # Adiciona um novo usuário
passwd user    # Altera a senha de um usuário
userdel user   # Apaga o usuário 
gpasswd -a user grupo  # Adiciona um usuário a um grupo
gpasswd -d user grupo  # Remove um usuário de um grupo
groupadd nome  # Cria um grupo
groupdel nome  # Exclui um grupo 
```

## 📜 Logs e Monitoramento

```sh
dmesg                 # Exibe mensagens do kernel
journalctl            # Exibe logs do sistema
cat /var/log/syslog   # Exibe logs gerais do sistema
tail -f /var/log/auth.log  # Monitora o log de autenticação em tempo real
```
