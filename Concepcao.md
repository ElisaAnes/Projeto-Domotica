# Concepção do Projeto: <h1>
  
## Requisitos <h2>
  Realizar um projeto de Domótica para uma casa, automatizando diversos processos, como ligar luzes em diferentes comodos, controlar a temperatura e umidade do ar, monitorar se há vazamento de gás, monitorar se ha tentativa de invasao e abrir o portão da garagem de forma inteligente, e para facilitar ainda mais a vida dos moradores, eles disponibilizarao de uma interface intuitiva para interacao em seu Notebook. 
  
### Componentes que serão utilizados: <h3>
 
 - Placa MEGA 2560 R3 + Fonte + Cabo USB para Arduino
 - Sensor Fotoresistor LDR de 5mm 
 - Sensor de Cor TCS3200
 - Sensor de Umidade e Temperatura DHT11
 - Sensor de presença e movimento PIR
 - Sensor de gás MQ-2 inflamável e fumaça
 - Sensor ultrasônico HC-SR04
 - Micro Servo SG92R 9g TowerPro
 - Módulo Sensor de Umidade/Nível Água Chuva
 - Módulo Relé 5 V e um Canal
 - Módulo Matriz de LED 8×8 com MAX7219
 - Buzzer passivo
 - Display LCD 16×2 I2C Backlight Azul
  
## Objetivo <h2>
  Os Objetivos sao: 
  - Realizar uma maquete semelhante aos exemplos abaixo;
  - Portão inteligente: quando o carro "cadastrado" chegar perto do portão, ele abrirá automaticamente, sem a necessidade de apertar o botao, depois que o carro passar, o portão fechará. Com o sensor de cor vamos simular uma inteligencia artificial, então a placa do carro cadastrado terá a cor x, o sensor identificará a cor x e abrirá o portão. Quando o portão abre, teremos um sensor de presença e movimento que manterá o portão aberto enquanto receber sinal, quando o carro passar pelo portão o sensor de presença nao terá mais sinal e então o portão fechará.
  - Casa em modo soneca: quando atingir 21 horas a casa entrará em modo soneca automaticamente, isso significa que a luminosidade da casa irá diminuir, para que a familia se prepare para dormir. Isso será feito através da programação do arduino (essa função pode ser desativada manualmente).
  - Conseguir controlar a casa atraves de uma interface intuitiva.
  - Receber notificacoes no Smartphone se algo acontecer, como invasao, vazamento de gas, esquecimento de luzes acessas.

### Modelo para maquete <h3>
  Abaixo temos um modelo de Casa que servirá de inspriração para maquete:
  
![Modelo Casa](https://github.com/ElisaAnes/Projeto-Domotica/blob/main/Plantas-de-Casas-de-Dois-Andares%20(1).jpg)
  <br />
  
### Modelo Planta Baixa da Maquete <h3>
  Abaixo temos a planta da maquete que será de dois andares
  
![Planta Baixa](https://github.com/ElisaAnes/Projeto-Domotica/blob/main/Plantas-de-Casas-de-Dois-Andares.jpg)
  
  #### Referências <h4>
  MUNDO DAS TRIBOS. Planta de Casas de dois andares. Disponível em: https://www.mundodastribos.com/plantas-de-casas-de-dois-andares.html . Acesso em: 6 nov. 2021.
