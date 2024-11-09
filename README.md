# Projeto Carro Telecomandado e Circuito Realista

### Versão 0.1

## Autor
_Nome do autor_

---

## Descrição

Este projeto tem como objetivo criar um sistema de condução de um carro telecomandado com uma experiência realista. Ele inclui uma pista fechada em madeira com controles de volante e pedais, checkpoints e um sistema de monitoramento de tempos. O condutor precisa completar voltas no menor tempo possível, com penalizações de tempo caso o carro colida com as barreiras do circuito. O sistema também utiliza LEDs e um display TFT para indicar penalizações e monitorar os tempos de volta.

### Funcionalidades Principais
- Controle do carro via volante e pedais.
- Circuito fechado em madeira com pontos de controle.
- Penalizações e sinalizações visuais (LEDs) em caso de colisão.
- Monitoramento de tempos em display TFT.

## Pré-requisitos

Para desenvolver e executar este projeto, você precisará dos seguintes materiais e dependências:
- **Hardware Necessário**:
  - Fios, Breadboards, Botões, LEDs
  - Display TFT
  - Estruturas em madeira
  - Volante e pedais
  - Carro RC
  - HC-05 (Bluetooth Serial)
  - Arduinos e resistores
  - Piezo disc

- **Dependências de Software**:
  - Arduino IDE com bibliotecas para controle de motores, LEDs e display TFT.
  - Bluetooth e drivers compatíveis com o HC-05.
  - Plataforma para monitoramento de tempos (ex: código de monitoramento para Arduino).

### Instalação e Configuração

1. **Conecte o Carro e o Sistema de Controle**:
   - Instale as bibliotecas no Arduino IDE para o display TFT, LEDs e comunicação Bluetooth.
   - Configure o HC-05 para se conectar ao sistema via Bluetooth.

2. **Construção do Circuito e Pista**:
   - Monte o circuito fechado em madeira com checkpoints e estrutura de apoio ao carro.
   - Configure LEDs e sensores de colisão ao longo da pista para indicar penalizações.

3. **Conecte e Calibre o Volante e os Pedais**:
   - Conecte o volante e pedais aos Arduinos e ajuste a sensibilidade para o controle preciso do carro.

## Execução e Modo de Funcionamento

Para iniciar o projeto, siga os passos abaixo:

1. **Iniciar a Conexão**:
   - Ligue o Arduino e o HC-05 e verifique a conexão Bluetooth com o carro RC.

2. **Posicione o Carro e Verifique os Checkpoints**:
   - Posicione o carro na linha de partida e verifique a leitura dos checkpoints na pista.

3. **Inicie a Condução**:
   - Controle o carro com o volante e os pedais, completando o circuito no menor tempo possível.
   - Caso ocorra uma colisão, os LEDs ao redor da pista piscarão em vermelho e haverá uma penalização de 1-2 segundos na volta.

## Parâmetros Disponíveis

- `tempo_penalizacao`: Tempo de penalização em caso de colisão (padrão: 2 segundos).
- `cor_leds_colisao`: Cor dos LEDs em caso de colisão (padrão: vermelho).
- `display_monitoramento`: Ativa ou desativa o display para monitoramento dos tempos.
- `sensibilidade_controlo`: Ajusta a sensibilidade do volante e pedais.

## Contribuições

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:
1. Faça um fork do projeto.
2. Crie um branch para suas modificações (`git checkout -b feature/nova-funcionalidade`).
3. Faça o commit das suas alterações (`git commit -am 'Adiciona nova funcionalidade'`).
4. Envie para o branch principal (`git push origin feature/nova-funcionalidade`).
5. Crie uma Pull Request.

## Licença

Este projeto é licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.
