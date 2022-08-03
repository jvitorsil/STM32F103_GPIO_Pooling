# STM32F103_GPIO_Pooling
## Sistema com microcontrolador para controle de pinos GPIO por Polling

O projeto conta com o controle de um LED por Pooling, no qual, ao acionar o switch a velocidade de piscagem do LED é alterada.

Para rodar o projeto é necessário um microcontrolador do modelo especificado e um depurador ST-LINK.

Arquivos:

```
Arquivo ".project" contem as especificações e ativação das portas utilziadas no microcontrolador
```
```
Pesta "app" contem todo o código desenvolvido para atividade, realizando o desacoplamento com a plataforma da ST, ou seja, não dependente da mesma

    arquivos app: chamadas das funções principais
    arquivos hw: definição de funções úteis
```




