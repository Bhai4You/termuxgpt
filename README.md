
<div align="center">

<img src="https://huggingface.co/parixit679/termuxgpt/resolve/main/assets/icon_round.png" width="140" alt="TermuxGPT icon">

# TermuxGPT

### A small on-device assistant for the TermuxGPT Android app

[![Get it on Google Play](https://img.shields.io/badge/Google%20Play-Get%20the%20app-34A853?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.codeninja.termuxgpt)

[![Website](https://img.shields.io/badge/Website-bhai4you.com-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://bhai4you.com)

![Base Model](https://img.shields.io/badge/Base-Qwen2.5--0.5B--Instruct-6C47FF?style=flat-square)
![Format](https://img.shields.io/badge/Format-LiteRT--LM-FF6F00?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![License](https://img.shields.io/badge/License-Apache--2.0-blue?style=flat-square)

</div>

---

## Model Details

| Property | Details |
|---|---|
| Model file | `termuxgpt.litertlm` |
| Model size | ~509 MB |
| Runtime | LiteRT-LM |
| Platform | Android |
| Execution | On-device CPU |
| Base model | `Qwen/Qwen2.5-0.5B-Instruct` |
| Base license | Apache-2.0 |
| Task | Text generation |

## About

TermuxGPT is a lightweight on-device language model designed for use with the **TermuxGPT Android app**.

The model is based on **Qwen2.5-0.5B-Instruct** and packaged in the **LiteRT-LM** format for local inference on Android devices.

It is intended to provide fast, private, and lightweight AI assistance directly on-device without requiring cloud inference for supported functionality.

## Features

- Runs locally on Android
- No cloud inference required for the local model
- Lightweight ~509 MB model
- Built on Qwen2.5-0.5B-Instruct
- Optimized for LiteRT-LM
- Designed for TermuxGPT
- Suitable for basic terminal and Linux-related assistance
- Works on CPU

## Screenshots

<div align="center">

<img src="https://huggingface.co/parixit679/termuxgpt/resolve/main/assets/strip1.png" width="100%" alt="TermuxGPT screenshots">

<br><br>

<img src="https://huggingface.co/parixit679/termuxgpt/resolve/main/assets/strip2.png" width="100%" alt="TermuxGPT screenshots">

</div>

## Base Model

This model is built from:

[Qwen/Qwen2.5-0.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-0.5B-Instruct)

Please refer to the original model repository for additional information about the architecture, training, limitations, and base model license.

## Runtime

The model is distributed in the LiteRT-LM format:

```text
termuxgpt.litertlm
```

It is intended to run locally on supported Android devices using LiteRT-LM.

Performance depends on device CPU, available RAM, Android version, and runtime configuration.

