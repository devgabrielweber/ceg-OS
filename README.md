# O Sistema Ceg-OS

Esse é um Sistema Operacional baseado no Ubuntu Linux 22.04.2 LTS desenvolvido por estudantes do Instituto Federal de Santa Catarina com o objetivo de facilitar o aprendizado de programação de estudantes que possuem deficiencias visuais.

#### **Faça o downlaod da iso através do link: https://www.jetdrop.net/F7eqIowP8Za#CwGgzAHCCsVgTCYA2GJ7AIwk6TAGReKDdXJKTWHMadaMAfWQCUAhAZwGUBHNgFwDuHAJ4A5ACoAzAA4ANNgEMAFi34AvAMaK2AaxEBhAOIBLACIBpIA **

## Diferencial do sistema:
* Leitor de tela integrado ao terminal de comandos mais responsível utilizando TDSR (https://github.com/tspivey/tdsr);
* Navegador da Web de texto integrado ao Terminal utilizando Lynx (https://lynx.invisible-island.net/);
* VScode instalado nativamente.

## Outras ferramentas disponíveis:
* Tema de alto-contraste;
* Leitor de tela para aplicações GUI;
* Seletor de tamanho da letra;
* Ferramenta de Lupa.

## Como acessar essas ferramentas?
### Instalação:
O Ceg-OS é um sistema operacional que pode ser tanto rodado em modo live quanto instalado em um computador. Para utilizálo, você deve preparar um USB Bootável, utilizando ferramentas como Rufus (para windows) ou Startup Disk Creator (para Linux) e a ISO disponibilizada.

### Como acessar os recursos:

#### Leitor de terminal (TDSR):
Se utilizado com o usuário ceg-os, esse SO automaticamente integra o uso do terminal com o leitor de tela TDSR, ou seja, **basta abrir o terminal para que o leitor de tela seja ativado**.
No entando, caso esteja utilizando outro perfil, você precisará adicionar a seguinte linha ao arquivo /home/<**SEU USUARIO**>/.bashrc: "/home/ceg-os/tdsr/tdsr";  
  
  Você pode fazer isso através do comando:  
  
  **nano /home/<**SEU USUARIO**>/.bashrc**;  
  
  e adicionando "/home/ceg-os/tdsr/tdsr" na última linha do arquivo aberto.

#### Navegador da web via terminal (lynx):
Para acessar o navegador Lynx, basta digitar "lynx <**Site que deseja acessar**>" e pressionar Enter no seu terminal.


#### Outras configurações de acessibilidade:
Para acessar outras configurações de acessiblidade, como o leitor de tela ORCA (lê a tela de todo sistema, não somente do terminal), acesse o aplicativo **configurações** e ative todas as opções que achar necessário. É nesse momento que você vai encontrar as configurações de modo de **modo de alto contraste, letras maiores, lupa, entre outras.**

**É importante ressaltar que talvez você precise ativar os recursos de acessibilidade nos programas que instalar / usar**.   
  
* No VSCode, você pode acessar algumas informações de acessibilidade através do atalho **shift+alt+f1**. Para obter mais informações, você também pode pressionar **ctrl+m** após o atalho anterior, ou acessar a página de acessibilidade do VSCode: https://code.visualstudio.com/docs/editor/accessibility
