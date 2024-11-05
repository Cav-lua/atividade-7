# **Cálculo de Salário App**

> Um aplicativo Android simples para calcular o novo salário baseado em um percentual de aumento.

## 📱 Descrição

O **Cálculo de Salário App** permite ao usuário inserir seu salário atual e escolher um percentual de aumento. O aplicativo calcula e exibe o novo salário com base na seleção do usuário.

## 🔧 Funcionalidades

- [x] Entrada de dados (salário atual)
- [x] Seleção de percentual de aumento através de radio buttons
- [x] Cálculo do novo salário com base no percentual selecionado
- [x] Exibição do resultado do novo salário

## 🎨 Design e Prototipagem

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. O design é simples e fácil de usar, com um fundo branco e textos em preto.
O usuário insere seu salário, escolhe o percentual de aumento e obtém o novo salário de forma clara.

## 🖥️ Telas do Aplicativo

1. **Tela Principal**

Na tela principal, o usuário insere seu salário atual em um campo de texto, seleciona um percentual de aumento utilizando radio buttons e clica no botão "Calcular novo Salário" para obter o novo valor.

![Captura de tela 2024-11-05 014222](https://github.com/user-attachments/assets/7acd8472-ad35-4d7d-bec0-d73febe0f751)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView** e **EditText** para entrada e exibição de dados
- [x] **RadioButton** para seleção do percentual de aumento
- [x] **Button** para acionar o cálculo do novo salário

## 👨‍💻 Desenvolvedores

Cav-lua - Desenvolvedor - [GitHub](https://github.com/Cav-lua)

## 📄 Licença

Este projeto está licenciado sob os termos da licença MIT. 

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:

    ```bash
    git clone https://github.com/Cav-lua/calculo-salario-app.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/com/example/myapplication
│   │   │   │   ├── MainActivity.java       # Classe para a Tela Principal
│   │   │   └── res
│   │   │       ├── layout
│   │   │       │   ├── activity_main.xml   # Layout da Tela Principal
│   │   │       ├── values
│   │   │           ├── strings.xml         # Strings usadas no app
│   │   │           ├── colors.xml          # Cores definidas no projeto
│   └── build.gradle                        # Configuração do Gradle
└── README.md                               # Este arquivo
