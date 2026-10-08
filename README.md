## Olá, eu sou o Andrey 👋

Estudante de Engenharia de Software, focado em **backend com Python**, e professor de robótica.
Aprendo construindo: APIs com mensageria, apps Android nativos e até a engenharia reversa
do protocolo de um robô educacional que não tinha documentação nenhuma.

No momento estou estudando arquiteturas com mensageria (RabbitMQ/Kafka) e serviços em containers.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrey-violante)

## 🌐 Conheça meu portfólio

<a href="https://andreyviolante.github.io">
  <img src="assets/portfolio.png" alt="Prévia do portfólio de Andrey Violante" width="100%">
</a>

<p align="center">
  <a href="https://andreyviolante.github.io">
    <img src="https://img.shields.io/badge/Acessar_o_portf%C3%B3lio-andreyviolante.github.io-0F7B6C?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Acessar o portfólio">
  </a>
</p>

## ⭐ Projetos principais

<h2 align="center">🗣️ <a href="https://englishtutor-weld.vercel.app">Hi, Kiara!</a></h2>

<p align="center">
  <a href="https://englishtutor-weld.vercel.app">
    <img src="assets/hi-kiara-app.png" alt="Tela inicial do Hi, Kiara! com a Kiara, assistente virtual de inglês" width="280">
  </a>
</p>

Assistente virtual de prática de inglês para alunos do 6º ao 9º ano. A **Kiara**, uma personagem animada,
conversa com o aluno por **texto e voz**: reconhecimento de fala para ouvir o aluno, voz sintetizada para responder.
A conversa se adapta ao ano escolar, ao nível e aos tópicos de gramática escolhidos.

O método é **socrático**: em vez de entregar a resposta, a Kiara devolve uma pergunta que leva o aluno a chegar nela.
Como o público é menor de idade, o comportamento da IA tem limites de segurança explícitos.
O código é privado, mas o app está aberto no link.

<p align="center">
  <a href="https://englishtutor-weld.vercel.app"><img src="https://img.shields.io/badge/Abrir_o_app-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Abrir o app"></a>
</p>

<p align="center"><sub>React Native · Expo · TypeScript · LLM · Reconhecimento de voz · Síntese de voz</sub></p>

<h2 align="center">🤖 <a href="https://github.com/AndreyViolante/Est-Robot">Est-Robot</a></h2>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/est-robot-dark.png">
    <img src="assets/est-robot-light.png" alt="Fluxo do Est-Robot: script Python, compilador, programa binário, envio por USB ao robô" width="560">
  </picture>
</p>

O robô educacional **Dr. Luck EST** só podia ser programado por uma IDE fechada e sem nenhuma documentação pública.
Capturei e analisei o tráfego USB, mapeei o **protocolo HID** e o formato binário dos programas, e escrevi um
**compilador** que transforma scripts Python no código que a máquina virtual do robô executa.

Resultado: o robô passa a ser programado em Python puro, sem depender da IDE proprietária. Uso o projeto
nas aulas de robótica e na preparação da equipe para a OBR.

<p align="center">
  <a href="https://github.com/AndreyViolante/Est-Robot"><img src="https://img.shields.io/badge/Ver_o_c%C3%B3digo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Ver o código"></a>
</p>

<p align="center"><sub>Python · Engenharia reversa · HID/USB · Compiladores · Robótica</sub></p>

## Outros projetos

<h3 align="center">💰 <a href="https://github.com/AndreyViolante/Finance-Ai">Finance-Ai</a></h3>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/flow-finance-ai-dark.png">
  <img src="assets/flow-finance-ai-light.png" alt="Fluxo do Finance-Ai: notificação do banco, lê o valor, guarda no celular, painel e meta" width="570">
</picture>

App Android de finanças pessoais que registra os gastos sozinho: lê as notificações de compra do banco,
extrai o valor e monta um painel com renda, despesas fixas, saldo livre e meta de economia. Os dados ficam só no celular.

<sub>React Native · Expo · TypeScript · Java · MMKV</sub>

<h3 align="center">📱 <a href="https://github.com/AndreyViolante/RegionWatcher">RegionWatcher</a></h3>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/flow-regionwatcher-dark.png">
  <img src="assets/flow-regionwatcher-light.png" alt="RegionWatcher compara o hash da área escolhida antes e agora e dispara um alerta quando muda" width="497">
</picture>

App Android que vigia uma área da tela e avisa quando ela muda, usando captura via MediaProjection
e comparação por hash perceptual (dHash).

<sub>Kotlin · Jetpack Compose · Foreground Service</sub>

<h3 align="center">🎓 <a href="https://github.com/AndreyViolante/Moodle-Assistente">Moodle-Assistente</a></h3>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/flow-moodle-assistente-dark.png">
  <img src="assets/flow-moodle-assistente-light.png" alt="Fluxo do Moodle-Assistente: API do Moodle, prazos por urgência, aviso no Windows, tutor com IA" width="595">
</picture>

Assistente de desktop para o AVA da faculdade. Consulta a API do Moodle, ordena as entregas por urgência,
avisa por notificação do Windows quando um prazo se aproxima e abre um tutor com IA que já leu o enunciado e os PDFs da atividade.

<sub>Python · API REST · CustomTkinter · Gemini</sub>

## Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)

---

Aberto a oportunidades de **estágio** e **backend júnior**. Me chama no [LinkedIn](https://linkedin.com/in/andrey-violante).
