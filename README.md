## Desenvolvimento e Entrega do Checkpoint 1 - Edge Computing and Computer Systems

**Nomes + RM dos integrantes:**
- Guilherme Akio - 98582
- Matheus Motta - 550352
- Guilherme Morais - 551981
- Fabrício Saavedra - 97631	
- Vinicius Buzato - 99125

**Turma:** 1ESPW

**Ano:** 2023

### Objetivo
Fomos contratados pela Vinheria Agnello para desenvolver um sistema de monitoramento a ser instalado no ambiente em que os vinhos são armazenados. O dono a Vinheria informou que a qualidade do vinho é influenciada diretamente pelas condições de temperatura, umidade e luminosidade do ambiente. Neste primeiro momento, propusemos ao dono da Vinheria um projeto em etapas, e aqui detalhamos a primeira delas, um sistema de monitoramento de luminosidade:
- Elaboramos um sistema utilizando Arduino que faz a captura das informações de luminosidade do ambiente utiliazndo um sensor LDR.
- De posse dos dados coletados, o sistema atua como um alarme, utilizando LEDs para sinalizar quando o a ambiente estiver OK, ou quando alguma grandeza estiver fora dos limites estipulados.  
- Quando a luminosidade se encontra em níveis inadequados, além do led é soada uma buzina (buzzer) por um tempo determinado (3 segundos, no caso de estar em uma faixa de alerta) ou ininterrupta (no caso de se encontrar em níveis críticos). 

### Desenvolvimento do projeto
O projeto foi desaenvolvido utilizando a aplicação web Autodesk Tinkercad, para a elaboração de protótipos e testagem de circuitos e códigos, e a plataforma Arduino, juntamente com seus componentes físicos, para a montagem efetiva do circuito.

E elaboração do circuito final, juntamente com seu código de execução, foi feita através de pesquisas por outros projetos que utilizassem sistemas semelhantes, como o uso de leds, sensor LDR e buzinas, e também consultas a outros códigos prontos com as funções desejadas no Tinkercad, forums da internet e a inteligência artificial ChatGPT, até que foi possível arquitetar esta versão final adaptada a nossa necessidade.

### Como executar o projeto
  Para executar o projeto serão necessários os seguintes softwares:
  - Autodesk Tinkercad (para reproduzir a simulação exibida em [Projeto no Tinkercad](Projeto no Tinkercad.jpg))
  - Arduino (juntamente com o código presente em [neste arquivo](CodigoArduino.txt))
  
  E também será necessário um kit básico de componentes físicos do Arduino, dos quais serão utilizados:
  
  - 1 Arduino Uno R3
  - 1 Protoboard
  - 1 Fotorresistor
  - 1 Piezo
  - 1 LED Verde
  - 1 LED Vermelho
  - 1 LED Amarelo
  - 3 Resistores 220 Ω 
  - 1 Resistor 10 kΩ 
  
  Para a montagem do circuito, basta reproduzir o modelo exibio em Projeto no [Projeto no Tinkercad](Projeto no Tinkercad.jpg) utilizando os combonentes físicos listados. Para execução, é necessário conectar a placa Arduino Uno R3 a um computador via USB para inserir o código presente em CodigoArduino.txt no programa Arduino e fazer o upload.
   
### Pré-requisitos
  Para execução do projeto é necessário conhecimento sobre o uso da plataforma Autodesk Tinkercad, e experiência com o uso do programa Arduino e de seus componentes físicos. É necessário também saber usos básicos da linguagem C++ para entendimento do código e ajustes necesários (como no nível de luminosidade captada e frequência da buzina, por exemplo).

### Video Explicativo
   "link do video"
