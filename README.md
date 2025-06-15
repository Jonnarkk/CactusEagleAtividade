<p align="center">
  <img src="https://media.licdn.com/dms/image/v2/C4D0BAQHdO6nGXObdaQ/company-logo_200_200/company-logo_200_200/0/1673387493595?e=2147483647&v=beta&t=9Pmefp5NsDDpSsmDzJ73oqb-FB2ijIhc9iuAlB_Y29M"/>
</p>

# Cactus Rockets Design

## Atividade da Cactus de fixação sobre o software de prototipagem EAGLE e GitHub

Esse repositório hospeda os arquivos da atividade proposta para o aprendizado de criação de novas bibliotecas a partir do software EAGLE
e também para a utilização do Git/GitHub.

## O que foi feito nesse projeto do EAGLE?
O projeto no EAGLE inclui:
* Criação de um dispositivo genérico com comunicação I2C
* Integração deste dispositivo com um ESP32
* Criação do layout da placa a partir da esquemática

<p align="center">
  <img src="https://github.com/user-attachments/assets/8fe4c2b0-6832-4afe-afbe-ed60bc0035ba">
  <h4 align="center">Dipositivo genérico criado no EAGLE</h4>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ae287ccb-df9b-411f-af6f-94bad7284774">
  <h4 align="center">Layout da placa criada</h4>
</p>

Os pinos criados para este equipamento são
- `Pino VCC`: Utilizado para a alimentação do circuito interno
- `Pino SDA`: Utilizado para transmisão de dados do dispositivo para o ESP32
- `Pino SCL`: Utilizado para sincronização dos clocks da comunicação I2C
- `Pino GND`: Utilizado para a alimentação do circuito interno

### Trainee
Guilherme Miller Gama Cardoso

<p align="center">
  <img src="https://github.com/user-attachments/assets/afc64275-ade5-4490-829c-d8e11eca7db9">
</p>
