## 🖥️ Comandos Básicos

```sh
ls      # Lista os arquivos e diretórios
pwd     # Mostra o diretório atual
cd      # Navega entre diretórios
mkdir   # Cria um novo diretório
rm      # Remove arquivos ou diretórios
cp      # Copia arquivos ou diretórios
mv      # Move ou renomeia arquivos e diretórios
cat     # Exibe o conteúdo de um arquivo
clear   # Limpa o terminal
```

## 📂 Gerenciamento de Arquivos

```sh
touch arquivo      # Cria um novo arquivo
rm -r diretório    # Remove diretórios e seus conteúdos
find /caminho -name "*.txt"  # Encontra arquivos por nome
locate arquivo     # Localiza um arquivo no sistema
df -h               # Mostra o uso do disco
du -sh diretório  # Mostra o tamanho de um diretório
```

## 🔧 Permissões e Proprietários

```sh
chmod 755 arquivo   # Altera as permissões de um arquivo
chown user:user arquivo  # Altera o proprietário de um arquivo
ls -l                # Lista arquivos com permissões detalhadas
```

## 📌 Processos e Recursos do Sistema

```sh
ps aux          # Lista todos os processos em execução
top             # Exibe o uso dos recursos do sistema
kill PID      # Finaliza um processo pelo ID
killall nome  # Finaliza todos os processos com um nome específico
htop            # Versão avançada do 'top' (pode precisar ser instalado)
```

## 📡 Rede e Conexões

```sh
ifconfig            # Exibe informações da interface de rede (obsoleto, use 'ip a')
ip a               # Mostra os endereços IP das interfaces de rede
ping host        # Testa a conectividade com um servidor
wget url         # Baixa arquivos da web
curl url         # Faz requisições HTTP
netstat -tulnp     # Mostra portas abertas e conexões ativas
```

## 📦 Gerenciamento de Pacotes (APT - Debian/Ubuntu)

```sh
sudo apt update              # Atualiza a lista de pacotes disponíveis
sudo apt upgrade             # Atualiza todos os pacotes instalados
sudo apt install pacote    # Instala um pacote
sudo apt remove pacote     # Remove um pacote
sudo apt autoremove          # Remove pacotes desnecessários
```

## 🛠️ Usuários e Grupos

```sh
su             # Troca para o usuário root
su user        # Troca para um usuário específico
whoami         # Mostra o usuário atual
id             # Mostra detalhes do usuário
adduser nome # Adiciona um novo usuário
passwd user  # Altera a senha de um usuário
usermod -aG sudo user  # Adiciona um usuário ao grupo sudo
```

## 📜 Logs e Monitoramento

```sh
dmesg       # Exibe mensagens do kernel
journalctl  # Exibe logs do sistema
cat /var/log/syslog  # Exibe logs gerais do sistema
tail -f /var/log/auth.log  # Monitora o log de autenticação em tempo real
```
