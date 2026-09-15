# 🎬 Cine Manual

> **Câmera manual profissional para Android.**  
> Controle total de ISO, obturador, foco e balanço de branco — direto no seu celular.

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)](#roadmap)
[![Versão](https://img.shields.io/badge/vers%C3%A3o-v0.1.0-blue)](#roadmap)
[![Plataforma](https://img.shields.io/badge/plataforma-Android-green)](#)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-yellow)](#)

---

## 📖 Sobre

O **Cine Manual** é um aplicativo de câmera manual para Android, escrito em **Kotlin** com a **Camera2 API**. Ele foi criado para quem quer controle real sobre a captura de imagem — sem depender do modo automático da câmera nativa.

Com o Cine Manual você ajusta manualmente:

- 🔵 **ISO** — sensibilidade do sensor
- ⏱️ **Velocidade do obturador** — tempo de exposição
- 🎯 **Foco** — distância focal em tempo real
- ☀️ **Balanço de branco** — temperatura de cor em Kelvin
- 🔒 **Trava AE / AF** — para consistência durante toda a captura

> O projeto é **open source**, **sem telemetria** e **sem coleta de dados**. Tudo roda localmente no seu aparelho.

---

## ✨ Recursos

| Recurso | Status |
|---|---|
| Preview da câmera (Camera2) | ✅ Implementado |
| Detecção de capacidades do hardware | 🚧 Em progresso |
| Sliders manuais (ISO, obturador, foco, WB) | 📋 Planejado |
| Captura de foto | 📋 Planejado |
| Gravação de vídeo | 📋 Planejado |
| Interface estilo câmera profissional | 🚧 Em progresso |

---

## 🗺️ Roadmap

- [x] Estrutura do projeto e repositório no GitHub
- [x] Página inicial (landing page)
- [x] Preview da câmera com Camera2 API
- [ ] Detecção de capacidades do hardware (ISO, exposição, foco)
- [ ] Sliders manuais de ISO, obturador, foco e WB
- [ ] Captura de foto e salvamento em `MediaStore`
- [ ] Gravação de vídeo com controles manuais
- [ ] Publicação na Google Play Store

---

## 🛠️ Tecnologias

- **Linguagem:** [Kotlin](https://kotlinlang.org/)
- **API da câmera:** [Camera2](https://developer.android.com/training/camera2)
- **Build:** [Gradle](https://gradle.org/)
- **IDE:** [Android Studio](https://developer.android.com/studio)
- **UI:** XML Views + Material 3

---

## 📱 Requisitos

- **Android 5.0 (API 21)** ou superior
- Câmera traseira funcional
- Recomendado: aparelho com suporte a `MANUAL_SENSOR`
- Espaço livre para armazenamento das fotos

---

## 🚀 Como compilar

```bash
git clone https://github.com/SEU_USUARIO/cine-manual.git
cd cine-manual
