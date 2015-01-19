# RISO-0.8
Recuperação de Imagem de Sistema Operacional

O RISO (Recuperação de Imagem de Sistema Operacional) é um sistema que recupera imagens em múltiplas máquinas simultaneamente. Para tal ele utiliza a tecnologia de Torrent pra transmitir as imagens de um servidor para os terminais.

Todo o sistema é baseado em distribuição Debian e, portanto, não há garantia de funcionamento em outras distribuições que não derivadas do Debian.

O script foi feito para recuperar até 2 sistemas ao mesmo tempo, 1 Linux e 1 Windows.

INSTALAÇÃO:

Dentro da pasta do RISO digite 'sudo make'

EXECUÇÃO:

A preparação do ambiente para instalação e execução do RISO é a parte mais demorada do processo. Primeiro deve-se criar a imagem, que servirá também como servidor. O particionamento deve ser feito de maneira que pelo menos metade do disco seja reservado para um sistema de manutenção, que deverá ser uma distribuição Debian. A outra metade deve ser dividida da maneira que se considerar mais adequado, entre 1 sistema Linux e 1 Windows. O GRUB a ser utilizado deve ser o da partição de manutenção (ou de recuperação).

ADEQUAÇÕES

Possibilidade de download de imagens muito grandes, erro de Grub resolvido, e foi retirado o While das funções de baixar imagens, agora e possível ter uma interface no cliente semelhante a do servidor.

