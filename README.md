<div align="center">

![Mobile-Flutter: Conhecendo a biblioteca Animations](capa.png)

# 📱 Flutter Animations - Projeto Hyrule

[![Flutter](https://img.shields.io/badge/Flutter-3.10.2-02569B?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.0.6-0175C2?logo=dart)](https://dart.dev)
[![Alura](https://img.shields.io/badge/Alura-BootCamp%20Santander%202025-00C86F)](https://www.alura.com.br)

Aplicativo mobile desenvolvido durante o curso **"Flutter: utilize animações da biblioteca Animations"** da [Alura](https://www.alura.com.br), como parte do **BootCamp Santander 2025** de desenvolvimento mobile.

[Sobre](#-sobre-o-projeto) • [Animações](#-animações-implementadas) • [Funcionalidades](#-funcionalidades) • [Tecnologias](#%EF%B8%8F-tecnologias) • [Instalação](#-instalação) • [Estrutura](#-estrutura-do-projeto) • [Autor](#autor)

</div>

---

## 📖 Sobre o Projeto

O **Hyrule** é um aplicativo mobile que demonstra a implementação de animações avançadas em Flutter utilizando a biblioteca **Animations**. O projeto combina conceitos modernos de Material Design com funcionalidades práticas, incluindo consumo de API REST e persistência de dados local.

Este projeto foi desenvolvido para aprofundar conhecimentos em:
- Criação de animações fluidas e performáticas
- Implementação de transições entre telas
- Aplicação de princípios de UX/UI com animações
- Boas práticas de desenvolvimento Flutter

![GIF da aplicação em execução](projeto.gif)

---

## 🎨 Animações Implementadas

O projeto explora quatro tipos principais de animações da biblioteca Animations:

### 🔄 OpenContainer
Transições fluidas entre containers que expandem para revelar conteúdo completo, criando uma experiência de navegação contínua e intuitiva.

### ↔️ SharedAxis
Animações de troca de conteúdo com movimento em eixos compartilhados, proporcionando transições suaves entre diferentes estados da interface.

### 📄 PageTransitionSwitcher
Implementação de transições personalizadas entre páginas, permitindo controle total sobre como o conteúdo aparece e desaparece.

### 🦸 Hero Widget
Animações de elementos compartilhados entre telas, criando uma continuidade visual que guia o usuário através da navegação.

---

## ✨ Funcionalidades

- 🔍 **Busca por Categorias**: Pesquisa de entradas através de uma API REST organizada por categorias (Monstros, Criaturas, Equipamentos, Materiais, Tesouros)
- 💾 **Persistência Local**: Sistema de armazenamento local utilizando Floor (SQLite) para dados offline
- ⭐ **Sistema de Favoritos**: Salve e gerencie suas entradas favoritas
- 🗑️ **Gerenciamento de Dados**: Visualize e delete entradas salvas
- 🎭 **Navegação Animada**: Transições suaves e intuitivas entre todas as telas
- 🌙 **Tema Dark**: Interface moderna em Material Design 3 com tema escuro

---

## 🛠️ Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias e bibliotecas:

- **[Flutter 3.10.2](https://flutter.dev)** - Framework de desenvolvimento multiplataforma
- **[Dart 3.0.6+](https://dart.dev)** - Linguagem de programação
- **[Animations 2.1.1](https://pub.dev/packages/animations)** - Biblioteca de animações Material Design
- **[Floor 1.4.2](https://pub.dev/packages/floor)** - Persistência de dados (ORM para SQLite)
- **[Dio 5.3.2](https://pub.dev/packages/dio)** - Cliente HTTP para requisições à API
- **[HTTP 1.1.0](https://pub.dev/packages/http)** - Cliente HTTP alternativo
- **Material Design 3** - Sistema de design do Google

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter os seguintes requisitos instalados:

- **Flutter SDK 3.10.2** ou superior
- **Dart SDK 3.0.6** ou superior
- **Android Studio** ou **VS Code** com extensões Flutter e Dart
- **Emulador Android/iOS** ou dispositivo físico
- Conhecimentos básicos de Flutter e Dart

---

## 🚀 Instalação

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/OYanEnrique/flutter-animations-alura-2.git
cd flutter-animations-alura-2
```

### 2️⃣ Instale as dependências

```bash
flutter pub get
```

### 3️⃣ Execute o projeto

```bash
flutter run
```

Ou utilize sua IDE preferida:
- **VS Code**: Pressione `F5` ou use o menu `Run > Start Debugging`
- **Android Studio**: Clique no botão ▶️ Run

---

## 📁 Estrutura do Projeto

```
lib/
├── main.dart                      # Ponto de entrada do aplicativo
├── controllers/                   # Controladores e lógica de negócio
│   ├── api_controller.dart       # Gerenciamento de requisições API
│   └── dao_controller.dart       # Gerenciamento do banco de dados
├── data/                         # Camada de dados
│   ├── api/                      # Serviços de API
│   └── dao/                      # Data Access Objects
├── domain/                       # Camada de domínio
│   ├── business/                 # Regras de negócio
│   └── models/                   # Modelos de dados
├── screens/                      # Telas do aplicativo
│   ├── categories.dart           # Tela de categorias
│   ├── results.dart              # Tela de resultados da busca
│   ├── details.dart              # Tela de detalhes
│   ├── favorites.dart            # Tela de favoritos
│   └── components/               # Componentes reutilizáveis
└── utils/                        # Utilitários e constantes
    ├── theme.dart                # Configuração de tema
    └── consts/                   # Constantes da aplicação
```

---

## 📚 Tópicos Abordados no Curso

- ✅ O que são animações e sua importância na UX
- ✅ Implementação de animações OpenContainer
- ✅ Criação de animações SharedAxis
- ✅ Uso do PageTransitionSwitcher
- ✅ Aplicação do Hero Widget para transições
- ✅ Princípios e boas práticas de Material Design
- ✅ Integração de animações com navegação Flutter
- ✅ Performance e otimização de animações

---

## 🎓 Aprendizados

Este projeto proporcionou conhecimentos fundamentais sobre:

- Como implementar animações que melhoram a experiência do usuário
- A importância das transições fluidas na navegação mobile
- Boas práticas para uso da biblioteca Animations
- Integração de animações com arquitetura de projeto organizada
- Balanceamento entre estética e performance

---

## 📱 Plataformas Suportadas

- ✅ Android
- ✅ iOS
- ✅ Web
- ✅ Windows
- ✅ Linux
- ✅ macOS

---

## Autor

<div align="center">

**Yan Enrique**

[![GitHub](https://img.shields.io/badge/GitHub-OYanEnrique-181717?logo=github)](https://github.com/OYanEnrique)

Desenvolvido com 💙 durante o BootCamp Santander 2025

</div>

---

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais como parte do curso da Alura.

---

## 🙏 Agradecimentos

- [Alura](https://www.alura.com.br) - Pelo excelente conteúdo do curso
- [Santander](https://www.santander.com.br) - Pela oportunidade do BootCamp 2025
- Comunidade Flutter - Pelo suporte e documentação

---

<div align="center">

⭐ Se este projeto te ajudou, considere dar uma estrela!

</div>
