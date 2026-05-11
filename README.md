# Catapulta - Grupo B4
Neste repositório, estão contidos os códigos relacionados ao acionamento da catapulta construída para a disciplina de Introdução a Projeto de Engenharia I. A catapulta será comandada por dispositivo programado para ESP32.
O código a ser inserido no ESP32 possui como função obter os comandos pelo Bluetooth do dispositivo celular para ajustar a distância do lançamento e acionar o mecanismo da catapulta.
O código a ser inserido no arduíno recebe os comandos enviados pelo ESP32 por Comunicação Serial e controla os motores de passo:
  - O primeiro motor, motor1, é acionado quando o arduíno recebe o comando "0" e possuirá como finalidade atuar como uma chave que realiza o lançamento
  - O segundo motor, motor2, rotaciona acoplado a um barbante para alterar o ângulo da catapulta. O arduíno receberá do aplicativo o número de passos correspondente à rotação necessária para atingir determinada distância.
