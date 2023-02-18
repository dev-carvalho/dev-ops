# WSL - Windows Subsystem for Linux

## Instalação do WSL2 (Windows Subsystem Linux) no Windows 10 e Windows 11
	
1. No Command Prompt (cmd), digite o comando **wsl --install** e <Enter> para instalação do WSL2 no Windows 10.

> - Instalando: Plataforma de Máquina Virtual
> - Plataforma de Máquina Virtual foi instalado.
> - Instalando: Subsistema do Windows para Linux
> - Subsistema do Windows para Linux foi instalado.
> - Instalando: Subsistema do Windows para Linux
> - Subsistema do Windows para Linux foi instalado.
> - Instalando: Ubuntu
> - Ubuntu foi instalado.

2. Agora Restart seu computador.
3. Inicie o Linux Ubuntu diretamente no Menu ou na barra de pesquisa do Windows.  

<br>

## Comandos úteis

Comando         | Finalidade
--------------- | ----------------- 
wsl --install Ubuntu-22.04                  | Instalar uma distribuição
wsl --set-default-version 2                 | Executa tudo no WSL2	
wsl --install --distribution Ubuntu-22.04 <br> wsl --install -d Ubuntu-22.04 | Instalar uma distribuição
wsl --unregister Ubuntu                     | retira da lista de distribuições registradas no WSL	
wsl --list <br> wsl -l                      | Listar distribuições instaladas
wsl --list --online <br> wsl -l -o          | Listar distribuições disponíveis
wsl --list --verbose <br> wsl -l -o         | Lista o status das distribuições instaladas
wsl --set-default Ubuntu-22.04 <br> wsl -s Ubuntu-22.04 | Define a distribuição como padrão.
wsl -t Ubuntu-22.04                         | Desligar a distribuição Linux
wsl --shutdown                              | Encerra imediatamente todas as distribuições em execução e a WSL2.
wsl --status                                | Mostra o status do Subsistema do Windows para Linux.
wsl --update [Options]                      | Se nenhuma opção for especificada, o kernel do WSL2 será <br> atualizado para a versão mais recente.
