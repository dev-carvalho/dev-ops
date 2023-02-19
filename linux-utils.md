## Utilitarios Linux 22.04

Bash       | Novo                | Exemplo       | Destaque util
---------- | ------------------- | ------------- | -------------
ls         | exa                 | alias ll='exa -la'                                         | super colorido e alegre
df         | pydf                | alias df='pydf -h'   c                                     | df detahado e super colorido e alegre
less	     | most                | alias less='most'                                          | Apresenta o arquivo
tail       | multitail           | multitail -s 2 -i /var/log/daemon.log -I /var/log/auth.log | Multiplos arquivos no mesmo tail
tracepath	 | mtr (My TraceRoute) | mtr -r -c 5 google.com                                     | Sofisticado trace route
traceroute | mtr (My TraceRoute) |                                                            |

<br>

### Referências
- [multitail](https://www.debuntu.org/how-to-tail-multiple-files-with-multitail/)
- [mrt (My TraceRoute) ](https://linuxhint.com/mtr-a-diagnostic-tool/)
