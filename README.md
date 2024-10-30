# **JDUber - InfinityTech**🚜

<p align="center">
<img src="scr/assets/Infinity-Apresentação.png" alt="InfinityTech">
</p>

### Autores 👥
- Agatha Cassari Benedicto
- Arthur Gouvea
- Felipe Chiozzotto Gozzani 
- `Juliana Barbosa Sandes` 
- Raissa Yukari Senoi

## Introdução 📃

* **Principal problema:** <br>
  O principal problema da John Deere é a dificuldade na localização e monitoramento eficiente dos rebocadores e carrinhos, impactando negativamente o fluxo de trabalho e a        produtividade. A falta de um sistema que identifique se os carrinhos estão vazios ou carregados gera atrasos na logística interna e desperdício de tempo. Isso resulta em        custos operacionais elevados e gargalos na movimentação de materiais, comprometendo a eficiência geral das operações.
 
* **Objetivos:** <br>
  Nosso objetivo é facilitar a localização e utilização dos carrinhos, reduzindo o tempo gasto pelos usuários. Vamos desenvolver um sistema integrado com sensores e               microcontroladores Arduino para monitorar continuamente o estado dos carrinhos. Isso permitirá que os operadores saibam imediatamente quando um carrinho está vazio,         
  aumentando a eficiência operacional e a produtividade geral. O sistema aprimorado garantirá uma resposta mais ágil e coordenada nas operações.

<p align="center">
<img src="scr/assets/JB-img.png" alt="JohnDeere">
</p>

## Desenvolvimento 💻
- Estamos utilizando o Node-RED para o site e o programa que gerencia o sensor de peso e a localização dos carrinhos. A WiFi.h conecta o ESP32 ao Wi-Fi e escaneia redes, enquanto a PubSubClient.h envia dados ao broker MQTT (Mosquitto). A HX711.h configura a balança e a ArduinoJson.h converte os dados para JSON, compatível com o Node-RED. Essas bibliotecas garantem uma integração eficiente entre hardware e software.
  
<p align="center">
<img src="scr/assets/Diagrama.png" alt="Diagrama">
</p>

### Solução IoT do ESP32 🌐

<p align="center">
<img src="scr/assets/NodeRed.png" alt="Node-red">
</p>

## Resultados ✅
- Estamos desenvolvendo um site para facilitar a visualização dos carrinhos de forma eficiente. Implementamos um programa que utiliza um sensor de peso para indicar se a balança está vazia ou ocupada. Além disso, o site também exibe a localização dos carrinhos, utilizando a conectividade Wi-Fi para determinar a posição exata de cada um. Dessa forma, conseguimos monitorar tanto o estado de carga quanto a localização em tempo real, proporcionando uma melhor gestão e controle dos carrinhos no ambiente.

<p align="center">
<img src="scr/assets/Hardware.jpeg" alt="Hardware">
</p>

<p align="center">
<img src="scr/assets/Site.png" alt="Site">
</p>

Clique aqui para acessar **toda a visualização da Apresentação** de nosso projeto: [Apresentação](https://www.canva.com/design/DAGFS6GM3Aw/0-2xlqHYrZxdfv8g3aQgjA/edit?utm_content=DAGFS6GM3Aw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton). 👈 <br>

Clique aqui para acessar **o video Explicativo** de nosso projeto: [Video](https://www.youtube.com/watch?v=fd72xDK9Gok). 👈 <br>
