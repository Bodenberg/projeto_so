# Instalação do Sistema Linux na Maquina Virtual (Oracle Virtual Box)
### Antes de começar primeiro vamos baixar a .iso (http://www.slitaz.org/pt/) e o software da Oracle o Virtual Box (http://www.oracle.com/technetwork/pt/server-storage/virtualbox/downloads/index.html).

**Após o termino do Download, podemos iniciar a instalação da maquina virtual, não há segredo para completar a instalação basta seguir os passos e clicar em próximo até a conclusão.**

Com o software instalado, basta inicia-lo.

Assim que ele Inicializar aparecerá uma tela chamada "**Oracle VM VirtualBox Gerenciador**".

######Siga os passos a abaixo para iniciar a configuração da Maquina Virtual:

1. Passo:
 * Clique no botão 'Novo';

2. Passo:
 * De um nome para a sua maquina, no segundo campo (chamado Tipo) selecione 'Linux' e no terceiro campo (chamado de Versão) selecione 'Others Linux (32bits)', clique em proximo;
 
3. Passo:
 * Na seleção da memoria, de a ele 512mb, clique em proximo;
 
4. Passo:
 * No Disco Rigido, selecione Criar um novo disco disco virtual, clique em criar e de a ele 60gb;
 * No tipo de Disco Rigido selecione a opção VDI (VirtualBox Disk Image);
 * No Armazenamento de disco rigido selecione dinâmicamente alocado, clique em criar.
 
---------------------------------------------------------------------------------

#####Agora iremos instalar o Sistema Linux na maquina Virtual.
 
 ######Siga os passos a abaixo para instalar o Sistema:
 
 1. Passo: 
  * De um clique na maquina virtual que acabou de criar e selecione configuração;
 
 2. Passo:
  * Vá para Armazenamento, na Arvore de Armazenamento clique no icone do cd;
  * No Atributos no campo de drive óptico selecione 'IDE Secundario Master', clique no icone do cd e procure a pasta com o arquivo .iso que você baixou;
  
 3. Passo:
  * Vá em Redes no Adapter 1 e Habilite Place de Rede;
  * No campo 'conectando a' selecione Placa em modo Bridje e clique em 'OK';
  
 4. Passo:
  * Selecione a maquina virtual em questão e clique em iniciar.
  
 ------------------------------------------------------------------------------------
 
 #####Agora iremos inicializar a instalação e a configuração do sistema.
 
 ######Siga os passos a abaixo:
 
 1. Selecione Slitaz Live.
 
 2. Selecione a linguagem que você utiliza, no meu caso selecionei 'Portugues - Brasil - ABNT2'.
 
 --------------------------------------------------------------------------------------
 
 ####Para Salvar a as configurações da maquina permanentemente:
 
 1. Quanto for fechar a Maquina Virtual, selecione 'Salvar Estado'.