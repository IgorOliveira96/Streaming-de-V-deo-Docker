# Streaming-de-Video-Docker

Inicialmente foi feito um container, utilizando uma imagem de um sistema Ubuntu.

![image1](https://user-images.githubusercontent.com/91999157/206600170-8f6786be-97a0-41b1-bc1d-b71355b821d2.png)

Então foi utilizado o comando "apt-get update" para atualizar o sistema e os pacotes.

![image2](https://user-images.githubusercontent.com/91999157/206600234-64faac04-576a-4c50-a66a-3867ada1cb86.png)

Após isso foi feito a instalação de algumas ferramentas, para utilizar na reprodução do vídeo, primeiramente foi instalado o D-Bus, uma ferramenta para auxiliar na comunicação entre vários programas.

![image3](https://user-images.githubusercontent.com/91999157/206600247-4580825a-8db6-419f-b611-1299e4d9afad.png)

Logo após terminar a instalação do D-Bus, foi realizado a instalação do PulseAudio, para ser possível a reprodução do áudio.

![image4](https://user-images.githubusercontent.com/91999157/206600269-77c36352-96d8-4a8a-bf5b-86882dd63bcc.png)

Com as ferramentas de auxílio todas instalados, então foi realizado a instalação de duas ferramentas para a reprodução do vídeo. Primeiro foi instalado o VLC media player.

![image5](https://user-images.githubusercontent.com/91999157/206600433-0a21287d-abb7-4337-9fd9-16b5c89be735.png)

Então foi realizado também a instalação do FFmpeg, para ser possível testar em dois players diferentes.

![image6](https://user-images.githubusercontent.com/91999157/206600490-b97a0ce0-169c-47c3-a60e-45132be969f3.png)

Com todas ferramentas instaladas e prontas para serem utilizadas, é necessário adquirir um vídeo para testar, então durante o progeto foi feito um vídeo de apenas um minuto para ser testado, através do comando foi realizado a cópia do arquivo de vídeo do computador para o container.

![image7](https://user-images.githubusercontent.com/91999157/206600552-4d32b81a-c1ef-4fc2-bbcc-d377d8abbac8.png)

Após isso através dos comandos "vlc play video.mp4" ou "ffplay video.mp4", foi possível executar o arquivo com vídeo e áudio no programa de escolha.

![image8](https://user-images.githubusercontent.com/91999157/206600524-015e2a56-4801-44f4-aad5-814a0f9d5db9.png)
