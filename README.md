# <H1> Correção de alguns erros da instalação do LOL usando o WINE em sistemas Linux </h1>

<h3> Alguns erros que acontecem podem ocorrer pelo fato de sua maquina não responder algumas funções do WINE, pode ser resolvido facilmente mudando nas configurações pela própria plataforma que você baixou o game (Lutris, PlayONLinux e etc). Porém alguns erros bem específicos não conseguem ser resolvidos tão diretamente, para isso irei colocar uma série de correções que pode ser feito, além de commitar alguns arquivos que podem ser úteis no local do arquivo </h3>


<h3> Um dos muito comuns é a queda Drástica de FPS em comparação com outros sistemas que tem suporte da Riot (Windows e MAC), isso se deve ao fato de que um Sistema ANTICHEAT foi inserido no jogo fazendo com que reconhecesse o WINE como um programa de terceiros. Para burlar isso, foram feitas algumas mudanças porém não tem muito para onde correr. </h3> 

<h3> Em algumas Distros dão conflito ao utilizarem componentes da NVIDIA, o mais comum é o problema da LIB, que diz que não foi instalada, isso pode ser concertada voltando uma versão anterior do Drive da NVIDIA, ou caso persistir instalar a LIB que estarei disponibilizando no diretorio o famoso "the following i386 libraries are required". </h3>

<h3> Muitos erros que os usuários cometem é apenas ir instalando o LOL pelo lutris sem instalar os pré requisitos como o zenity, colocarei o código a frente para caso seja o seu erro de compatibilidade </h3> 

<h2> sudo apt install zenity openssl </h2>
