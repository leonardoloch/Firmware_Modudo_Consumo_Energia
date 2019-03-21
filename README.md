# Firmware_Modudo_Consumo_Energia

O software em questão é o firmware que foi inserido no módulo responsável por coletar o consumo de energia elétrica e enviar para o broker 
do mqtt. Assim que energizado o modo se comporta como access point para que o usuário faça seu setup inicial, seja ele rede, senha 
do wifi, informações do equipamento monitorado. Logo após o módulo encerra o modo access point e começa a se comporta como um um slave 
para os sistema, enviando as informações ou recebendo do servidor.
