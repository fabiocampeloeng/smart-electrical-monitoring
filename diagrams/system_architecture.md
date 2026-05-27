# Arquitetura Inicial do Sistema

## Fluxo do Sistema

Sensores elétricos realizam a aquisição dos parâmetros elétricos do sistema.

Os sinais são processados pelo ESP32, responsável pela leitura e transmissão dos dados utilizando protocolo MQTT.

Os dados são enviados para uma plataforma supervisória baseada em Node-RED, permitindo:

- monitoramento remoto;
- visualização em tempo real;
- geração de alarmes;
- registro de eventos elétricos.

## Estrutura Simplificada

Sensores → ESP32 → MQTT → Node-RED → Dashboard

## Objetivo

Desenvolver um sistema inteligente de monitoramento elétrico com potencial aplicação em:

- smart grids;
- grupos geradores;
- instalações elétricas;
- manutenção preditiva;
- diagnóstico de falhas.
