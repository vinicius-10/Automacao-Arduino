# 🏠SmartTech

> Projeto desenvolvido na disciplina de Prática e Desenvolvimento de Sistemas (Curso Técnico).
<div align="left">
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/Linguagem-PHP-orange" alt="Linguagem">
  <img src="https://img.shields.io/badge/Hardware-Arduino-blue" alt="Hardware">
  <img src="https://img.shields.io/badge/Interface-Web-orange" alt="Web">
</div>

## 📄 Sobre o Projeto

Este projeto consiste em uma solução de **IoT (Internet das Coisas)** para automação residencial simples. O objetivo é permitir o controle remoto de dispositivos elétricos (lâmpadas, ventiladores, etc.) através de uma interface web amigável, gerenciando quem tem acesso e registrando todas as atividades.

O sistema faz a ponte entre uma aplicação web e o microcontrolador Arduino, que atua fisicamente nos relés para ligar ou desligar a energia dos aparelhos.

## 🚀 Funcionalidades Principais

### 🔌 Controle de Dispositivos
* **Acionamento Remoto:** Ligar e desligar aparelhos conectados aos relés através do navegador (celular ou computador).
* **Status em Tempo Real:** Visualização se o aparelho está ligado ou desligado no momento.

### 👥 Gestão de Usuários
* **Controle de Acesso:** Sistema de login para garantir que apenas pessoas autorizadas controlem a casa.
* **Permissões por Aparelho:** Configuração de quais aparelhos cada usuário tem permissão para controlar (ex: Usuário X só controla o quarto, Usuário Y controla a casa toda).

### ⏰ Automação e Agendamento
* **Programação:** Funcionalidade para agendar o ligamento ou desligamento automático de aparelhos (Timer).

### 📊 Monitoramento
* **Histórico de Uso:** Log completo mostrando qual usuário acionou qual aparelho e em que horário, garantindo segurança e controle.

---

## 🛠️ Tecnologias e Hardware

### 💻 Software (Web & Banco de Dados)
* **Back-end:** [PHP / Node.js / Python]
* **Front-end:** [HTML, CSS, JavaScript]
* **Banco de Dados:** [MySQL / SQLite]
* **Comunicação:** [Serial / HTTP via Ethernet Shield]

### ⚡ Hardware
* **Microcontrolador:** Arduino [Uno / Mega]
* **Atuadores:** Módulo Relé [4 canais / 8 canais]
* **Conectividade:** [Ethernet Shield W5100 / ESP8266 / Via USB Serial]
* **Outros:** Jumpers, Protoboard.

---


## 🔧 Como Executar

### 1. Configuração do Hardware
1. Carregue o código `.ino` (pasta `/arduino`) na placa utilizando a Arduino IDE.
2. Monte o circuito conforme o esquema elétrico (conectar relés nas portas digitais definidas no código).

### 2. Configuração do Sistema Web
1. Importe o arquivo `banco.sql` para o seu gerenciador de banco de dados.
2. Configure a conexão com o banco no arquivo de configuração do site.
3. Inicie o servidor local (ex: XAMPP, Apache ou Node Server).
4. Acesse via navegador: `http://localhost/seu-projeto`.

---

## ✒️ Autores

* **Vinicius Souza Dias**
* **Sther dos Reis**
* **Fernanda Carvalho**
* **Emily Meireless**

---
