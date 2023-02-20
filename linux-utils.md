### Mostrar o logotipo da distribuição e informações do sistema do Linux em arte ASCII no terminal

```bash
sudo apt install neofetch
```
![image](https://user-images.githubusercontent.com/93828234/219990816-f3d6c8a3-2495-4300-b295-8df17128f8c5.png)

#### Referências
- https://livreeaberto.com/mostrando-logo-linux-em-ascii

<br>

## Utilitarios Linux 22.04

Bash       | Novo                | Exemplo       | Destaque util
---------- | ------------------- | ------------- | -------------
ls         | exa                 | alias ll='exa -la'                                         | Lista de arquivos super colorido e alegre
df         | pydf                | alias df='pydf -h'                                         | df detahado e super colorido e alegre
less	     | most                | alias less='most'                                          | Apresenta o arquivo
tail       | multitail           | multitail -s 2 -i /var/log/daemon.log -I /var/log/auth.log | Multiplos arquivos no mesmo tail
tracepath	 | mtr (My TraceRoute) | mtr -r -c 5 google.com                                     | Sofisticado trace route
traceroute | mtr (My TraceRoute) |                                                            |

#### Referências
- [multitail](https://www.debuntu.org/how-to-tail-multiple-files-with-multitail/)
- [mrt (My TraceRoute) ](https://linuxhint.com/mtr-a-diagnostic-tool/)

<br><br>

## OH-MY-BASH 
> Instale ***oh-my-bash***, por um bash mais colorido e alegre 
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"
``` 

#### Referências
- INSTALAÇÃO - https://terminalroot.com.br/2019/05/conheca-e-instale-o-oh-my-bash.html
- OH-MY-BASH - https://github.com/ohmybash/oh-my-bash
 
<br>

## figlet

```bash
apt install figlet
``` 

```bash
01:51:33 root@i7ultra / → figlet Karvalho
 _  __                     _ _
| |/ /__ _ _ ____   ____ _| | |__   ___
| ' // _` | '__\ \ / / _` | | '_ \ / _ \
| . \ (_| | |   \ V / (_| | | | | | (_) |
|_|\_\__,_|_|    \_/ \__,_|_|_| |_|\___/
``` 

