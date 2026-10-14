[README.txt](https://github.com/user-attachments/files/33435432/README.txt)
Esse aplicativo foi criado para auxiliar futuros projetos de matrix de LED realizados por alunos de SDM, é gratuito, e permito que seja feita alterações para servir qualquer função extra, ou para qualquer alteração no código para adaptção na leitura das imagens para a matrix no código em C.

Execute o arquivo .EXE, e então basta selecionar o arquivo da sua imagem atráves do botão de navegar arquivos, a imagem será exibida para confirmação e visualização, em sequência extraia a informação dos pixeis com o botão de mesmo nome, essas informações serão exibidas em uma caixa de texto logo abaixo da imagem e dos botões. Ajuste o tamanho da janela caso não esteja inicialmente visível.
Na caixa de texto a conversão já estará formatada para colocar no código, no formato que fizemos o Jogo da memória, EM C.

Pixeis pretos são considerados "transparentes", no caso da matrix de led, seriam leds que estariam desligados. O código se limita a poucas cores para otimização de espaço ao enviar ao enviar como fase para microcontrolador, e quando uma cor não corresponde as cores disponíveis, ele escolherá a cor mais próxima. 

Evite tentar extrair informação de pixel da imagem placeholder, sua resolução é alta e causa problemas na interface, congelando o aplicativo, isso se aplica a qualquer imagem de alta resolução, limite-se a imagens menores que 500x500 pixels.


CRIADO POR ERICK VOSS DE OLIVEIRA
UDESC CCT JOINVILLE
Última alteração: 14/10/2026 - 09:44
