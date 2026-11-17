# 🚗 Velocímetro Automotivo HUD v2.0 - Telemetria GPS de Alta Precisão & Barra de LED RPM

[![Download APK](https://img.shields.io/badge/Download_APK-VelocimetroAutomotivo.apk-00F0FF?style=for-the-badge&logo=android)](https://github.com/lokaovida-eng/VelocimetroAutomotivo/releases/download/v2.0.0/VelocimetroAutomotivo.apk)
[![Version](https://img.shields.io/badge/Version-2.0.0-00FF66?style=for-the-badge)](https://github.com/lokaovida-eng/VelocimetroAutomotivo)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.22-7F52FF?style=for-the-badge&logo=kotlin)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?style=for-the-badge&logo=android)](https://developer.android.com/jetpack/compose)

**Velocímetro Automotivo HUD** é um aplicativo Android de telemetria GPS e monitoramento de viagens de alta precisão. Projetado com **100% de transparência Edge-to-Edge**, **feedback tátil de baixa latência**, **tipografia 3D neon para velocidade** e uma **barra de LEDs de troca de marcha com resposta ultra-rápida (90 ms)**.

---

## 🚀 Principais Características

### ⚡ Barra de LEDs de RPM / Shift Light (Resposta 90ms)
- **16 Segmentos LED Multicores (`#00FFCC` ➔ `#00FF66` ➔ `#FFFFCC00` ➔ `#FFFF0055`)**: Aumentam velozmente ao pisar no acelerador, simulando as luzes de troca de marcha de carros de corrida.
- **Tipografia Neon 3D Dinâmica**: Digitos digitais com contorno em brilho 3D e mudanças de cor conforme a velocidade.
- **100% Zero Bordas Pretas**: Layout Edge-to-Edge para a Tela de Capa (*Flex Window*) do Samsung Galaxy Z Flip 5 / 6 e smartphones padrão.

### 📱 Tela de Capa do Samsung Galaxy Z Flip & Widgets
- **Integração Nativa com Tela de Capa**: Suporte completo para os widgets da Tela de Capa do Z Flip via Samsung Good Lock / MultiStar.
- **Sincronização em Tempo Real**: Atualização instantânea na tela inicial e no widget da capa durante a condução.

### ⏱️ Telemetria GPS de Baixa Latência
- **Sincronização GPS 100ms**: Atualizações com latência mínima e filtragem de ruído para resposta imediata do velocímetro.
- **Contador Automático de Viagem**: Registra o tempo ativo e a distância percorrida (`KM`).

---

## 📥 Download Direto do APK (Release Oficial v2.0.0)

Baixe o instalador compilado **VelocimetroAutomotivo.apk** (v2.0.0) diretamente no seu dispositivo:

👉 **[Baixar Velocímetro Automotivo APK (v2.0.0)](https://github.com/lokaovida-eng/VelocimetroAutomotivo/releases/download/v2.0.0/VelocimetroAutomotivo.apk)**

---

## 🛠️ Especificações Técnicas

| Recurso | Tecnologia |
| :--- | :--- |
| **Linguagem** | Kotlin `1.9.22` |
| **Interface** | Jetpack Compose `2024.02.00` (Material 3) |
| **Min SDK** | `26` (Android 8.0 Oreo) |
| **Target SDK** | `34` (Android 14) |
| **Sistema de Build** | Gradle `8.5` |

---

## 📁 Estrutura do Repositório

```text
VelocimetroAutomotivo/
├── VelocimetroAutomotivo.apk           # Instalador Direto Compilado
├── app/
│   ├── build.gradle.kts
│   └── src/
│       └── main/
│           ├── AndroidManifest.xml
│           ├── java/com/eagleuno/app/
│           │   ├── VelocimetroActivity.kt        # Interface HUD e Lógica Neon RPM
│           │   ├── NormalWidgetProvider.kt       # Provider do Widget da Tela Inicial
│           │   └── CoverScreenWidgetProvider.kt  # Provider do Widget da Capa Z Flip
│           └── res/
│               ├── layout/                       # Layouts XML dos Widgets
│               └── values/                       # Temas e Textos
├── build.gradle.kts
└── README.md
```

---

## 👨‍💻 Desenvolvedor & Licença

Desenvolvido pela equipe **lokaovida-eng / Velocímetro Automotivo**.  
Licenciado sob a [Licença MIT](LICENSE).
