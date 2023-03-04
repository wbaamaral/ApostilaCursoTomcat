# Estudo do curso Servidores com Tomcat

<p align="justify">Esse repositório faz parte do meu estudo no curso de <a href="https://nova.escolalinux.com.br/course/servidores-com-tomcat">Servidores com Tomcat</a>, 
que está disponível na Escola Linux.</p>

<p align="justify">Nesse curso, eu aprendi a criar, configurar, administrar e monitorar servidores Java com Tomcat. Agora, eu sou capaz de criar e administrar servidores web em Java com maestria, graças às habilidades adquiridas no curso. O Tomcat é um dos servidores Java mais utilizados do mundo e é uma ferramenta essencial no mercado de TI.</p>

<p align="justify">Com a ajuda do instrutor Murilo Billia, eu aprendi tudo o que precisava saber para criar o meu primeiro servidor, desde a instalação e configuração do ambiente até o hardening e tunning do server. Eu recomendo esse curso para qualquer pessoa interessada em aprimorar suas habilidades em servidores Java com Tomcat.</p>

# O repotitório

<p align="justify">Para esse pequeno projeto de estudos, será utilizada a tecnologia de git lfs.
Git LFS (Large File Storage) é uma extensão do Git que permite lidar com arquivos grandes, como imagens, áudio e vídeo, de forma mais eficiente.</p>

<p align="justify">Sem o Git LFS, quando adicionamos um arquivo grande ao repositório do Git, ele é armazenado como um blob, que é basicamente uma cópia do arquivo completo. Isso pode tornar o repositório muito grande e dificultar a sua utilização.</p>

<p align="justify">Com o Git LFS, em vez de armazenar o blob diretamente no repositório do Git, ele é armazenado em um servidor remoto e substituído por um pequeno ponteiro. Assim, o repositório do Git não fica inchado com arquivos grandes, e quando precisamos desses arquivos, o Git LFS os baixa automaticamente do servidor remoto.</p>

<p align="justify">O Git LFS é útil para equipes que trabalham com arquivos grandes, pois permite gerenciar esses arquivos de forma mais eficiente e compartilhá-los com mais facilidade. Além disso, é fácil de usar e é compatível com vários serviços de hospedagem de código, como o GitHub e o Bitbucket.</p>

## Clonando o repositório

Para clonar este repositório, utilize o comando:


# Clonando e Atualizando Objetos LFS

Para clonar um repositório que usa Git LFS, é necessário ter o Git LFS instalado em sua máquina. Para isso, basta seguir as instruções de instalação encontradas na documentação oficial do Git LFS.

Com o Git LFS instalado, é possível clonar o repositório normalmente, usando o comando `git clone`:

`git clone https://github.com/wbaamaral/apostilacursoadministracaotomcat.git`

Após o clone, é necessário fazer o download dos objetos LFS usados no repositório. Para isso, basta executar o seguinte comando:

`git lfs pull`

Isso fará com que todos os objetos LFS sejam baixados para sua máquina.

Caso seja necessário atualizar os objetos LFS no repositório, basta executar o comando:


`git lfs fetch`


Isso fará com que o Git LFS verifique se há objetos LFS novos ou atualizados no repositório, e fará o download desses objetos, se necessário.

`git lfs checkout`

Com esses comandos, é possível clonar e manter atualizados repositórios que usam Git LFS, sem precisar de conhecimentos muito técnicos.
