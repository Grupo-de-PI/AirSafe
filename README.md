🏭 AirSafe - Monitoramento de Amônia em Frigoríficos
Sistema integrado com Arduino (MQ-2), Node.js e Dashboard em tempo real

Diagrama do Sistema (adicione um diagrama real do fluxo de dados)

📌 Objetivo
Monitorar concentração de amônia (NH₃) em câmaras frigoríficas usando:

Arduino Uno R3 + Sensor MQ-2 para coleta de dados.

Node.js como backend (API REST e comunicação serial).

MySQL para armazenamento histórico.

Dashboard com Chart.js para visualização em tempo real.

🛠 Tecnologias
Componente	Função
Arduino Uno R3	Leitura do sensor MQ-2 e envio via serial
Sensor MQ-2	Detecção de gases (amônia, CO, fumaça) - requer calibração para NH₃
Node.js	API REST, comunicação serial com Arduino e conexão MySQL
MySQL	Armazenamento de dados históricos
Chart.js	Visualização interativa dos dados no frontend
