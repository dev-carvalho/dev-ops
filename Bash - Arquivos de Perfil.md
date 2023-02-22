## Arquivos de Perfil do Bash

#### Os arquivos do /etc são globais, e valem para todos os usuários

- **/etc/profile**: Arquivo global de configuração de Perfil de todos os usuários; 
- **/etc/profile.d**: Diretório de scripts que são carregados pelo /etc/profile;
- **/etc/bashrc** ou **/etc/bash.bashrc**: Arquivo global de configuração de Perfil executado quando o Bash é carregado;

#### Os arquivos do HOME, são individuais para cada usuário;

- **~/.bash_profile**: Arquivo de Perfil individual de cada usuário;
- **~/.bash_login**: executa se ~/.bash_profile não existir;
- **~/.profile**: executa se .bash_profile e .bash_login não existirem;
- **~/.bashrc**:  Executado quando o Bash é iniciado;
- **~/.bash_logout**: Executado no logout;

*Os arquivos que tem profile no nome, são carregados no processo de login, uma única vez;* <br>
*Os arquivos que tem bash no nome são carregados toda vez que o Bash é executado.*


<img style="width: 800px; height:auto;" src="https://learnlinux.com.br/editor/files/login_pt.jpg">

#### Referências
- https://www.certificacaolinux.com.br/perfil-de-usuarios-no-linux/


