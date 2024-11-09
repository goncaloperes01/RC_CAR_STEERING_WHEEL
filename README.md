# RC Car Project with Realistic Driving Experience

### v0.1
### **Autor:** Gonçalo Peres e Guilhermem Serra

### Descrição do Projeto
Este projeto visa criar uma experiência inovadora e desafiadora com um carro telecomandado e uma pista personalizada. O carro será controlado através de um volante e um conjunto de pedais, proporcionando uma condução mais realista. A pista será um circuito fechado em madeira, onde o objetivo é completar cada volta no menor tempo possível, evitando penalizações devido a colisões.

**Principais Funcionalidades:**
- Controlo do carro por volante e pedais.
- Pista fechada com checkpoints e linha de partida/meta.
- Penalizações automáticas e indicação visual (LEDs vermelhos) em caso de colisão.
- Display de monitorização com tempos e dados da volta em curso.

### Data de Lançamento
<!-- Podes adicionar a data de lançamento aqui -->

---

## Pré-requisitos

Para a construção e funcionamento do projeto, são necessários os seguintes componentes e ferramentas:
- **Hardware:** Arduinos, Carro RC, Volante e pedais, Display TFT, Leds, HC05 Serial Bluetooth Brick, Breadboards, Resistências, Fios, Botões, Estruturas de madeira.
- **Software:** Código em Arduino IDE, configuração de ligações Bluetooth e Wi-Fi, interface de monitorização.

### Instruções de Construção e Instalação

1. **Montagem da Pista:**
   - Construa a pista em madeira com uma linha de partida/meta e checkpoints.
   - Instale LEDs ao longo da pista para indicação visual de penalizações.

2. **Configuração do Carro RC:**
   - Realize a calibração inicial da velocidade do carro e a configuração dos sensores de colisão e checkpoints.
   - Conecte o sistema de controlo Bluetooth e Wi-Fi para comunicação com o carro.

3. **Instalação do Volante e Pedais:**
   - Integre o volante e pedais com o Arduino para controlar a velocidade e direção do carro.

4. **Configuração do Display TFT:**
   - Configure o display para mostrar os tempos de cada volta e os melhores resultados.

5. **Testes e Ajustes Finais:**
   - Realize testes de estabilidade do carro e afine o sistema de penalizações e checkpoints.

---

## Começando a Utilizar

1. **Executar o Projeto:**
   - Ligue o sistema e conecte o carro RC à rede Bluetooth.
   - Posicione o carro na linha de partida.
   - Utilize o volante e pedais para controlar o carro na pista.

2. **Modos de Funcionamento:**
   - **Modo de Corrida:** Completar voltas no menor tempo possível.
   - **Modo de Treino:** Praticar voltas sem penalizações.
   - **Modo de Monitorização:** Visualizar tempos e penalizações no display em tempo real.

---

## Parâmetros e Configurações Disponíveis

- **Velocidade do Carro:** Configurável através do código Arduino.
- **Duração das Penalizações:** Ajustável entre 1 a 2 segundos por colisão.
- **Nível de Sensibilidade dos Checkpoints:** Ajustável para garantir contagem precisa das voltas.
- **Indicação Visual de Penalizações:** LEDs vermelhos ao redor da pista.
- **Atualização de Tempos no Display:** Atualizações a cada checkpoint.

---

## Notas Importantes

- É essencial manter o carro calibrado para evitar erros de contagem de voltas.
- Recomenda-se realizar testes regulares no sistema de controlo e monitorização para assegurar a precisão das leituras.

---

## Como Contribuir

Contribuições são bem-vindas! Para contribuir:
1. Clone o repositório e crie uma nova branch para a sua funcionalidade ou correção.
2. Faça commit das suas alterações e envie um pull request.
3. Detalhe as alterações feitas no seu pull request para uma revisão mais rápida.

---

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT). Sinta-se à vontade para utilizá-lo e modificá-lo conforme necessário.
