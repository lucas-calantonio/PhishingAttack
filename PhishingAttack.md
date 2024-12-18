# Phishing para Captura de Senhas do Google 🚨

Este repositório contém as etapas para realizar um ataque de phishing utilizando **Kali Linux** e **setoolkit**, com o objetivo de capturar credenciais de login do Google.

## 🛠️ Ferramentas Necessárias
- **Kali Linux** 🐧
- **setoolkit** 🧰

## Configurando o Phishing no Kali Linux ⚙️

### 1. Acesso root 🔐
Para obter acesso root, execute o seguinte comando:

```bash 
sudo su
```

### 2. Iniciando o setoolkit 🛠️
No terminal, digite o comando abaixo para iniciar o setoolkit:

```bash 
setoolkit  
```

### 3. Selecione o Tipo de Ataque 🎯
Escolha a opção Social-Engineering Attacks.

### 4. Selecione o Vetor de Ataque 🌐
Escolha a opção Web Site Attack Vectors.

### 5. Escolha o Método de Ataque 🔓
Selecione Credential Harvester Attack Method.

### 6. Selecione o Template de Ataque 📄
Escolha a opção Web Templates.

### 7. Obtenha o Endereço IP da Máquina 🖧
Use o comando abaixo para descobrir o endereço IP da sua máquina:

```bash 
ifconfig
```

### 8. URL para Clone de Página 🔗
Utilize a URL abaixo para criar a página de phishing que imita o Google:

```bash
http://www.google.com/
```

### 📊 Resultados
Após a execução do ataque, o setoolkit irá registrar as credenciais capturadas. As informações estarão disponíveis para visualização no terminal ou no arquivo de log gerado.

![Captura de tela 2024-12-17 230316](https://github.com/user-attachments/assets/d6b46a2a-218b-4803-9646-4d310d8a521f)

