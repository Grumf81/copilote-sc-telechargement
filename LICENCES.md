# Composants tiers inclus dans l'installateur

Chaque composant reste sous la licence de son auteur. Les textes complets sont sur les pages indiquées.

| Composant | Auteur | Licence | Source |
|---|---|---|---|
| Python 3.13 (python-build-standalone) | Python Software Foundation, Astral | PSF License | https://github.com/astral-sh/python-build-standalone |
| Bibliothèques Python (faster-whisper, vosk, sherpa-onnx, Flask…) | leurs auteurs respectifs | licences libres, voir chaque paquet dans `.venv\Lib\site-packages` | https://pypi.org/ |
| segno (QR code d'appairage du téléphone) | Lars Heuer | BSD 3-Clause | https://github.com/heuer/segno |
| uv | Astral | MIT / Apache 2.0 | https://github.com/astral-sh/uv |
| llama.cpp | ggml-org | MIT | https://github.com/ggml-org/llama.cpp |
| Qwen 2.5 3B Instruct (IA locale, composant facultatif) | Alibaba Cloud (Qwen) | **Qwen Research License** : usage non commercial | https://huggingface.co/Qwen/Qwen2.5-3B-Instruct-GGUF |
| Whisper small (faster-whisper) | OpenAI, conversion Systran | MIT | https://huggingface.co/Systran/faster-whisper-small |
| Whisper large-v3-turbo (faster-whisper, composant NVIDIA) | OpenAI, conversion Mobius Labs | MIT | https://huggingface.co/mobiuslabsgmbh/faster-whisper-large-v3-turbo |
| Vosk small fr 0.22 | Alpha Cephei | Apache 2.0 | https://alphacephei.com/vosk/models |
| Silero VAD | Silero Team | MIT | https://github.com/snakers4/silero-vad |
| CAM++ (empreinte vocale, 3D-Speaker) | Alibaba DAMO Academy | Apache 2.0 | https://github.com/modelscope/3D-Speaker |
| Voix Piper fr_FR-siwis-medium | Rhasspy / jeu de données SIWIS | CC BY 4.0 | https://huggingface.co/rhasspy/piper-voices |
| Voix Piper fr_FR-tom-medium | Rhasspy | AGPL v3 | https://huggingface.co/rhasspy/piper-voices |
| espeak-ng (données de prononciation des voix) | espeak-ng | GPL v3 | https://github.com/espeak-ng/espeak-ng |
| OpenVoice v2 (convertisseur de voix) | MyShell | MIT | https://github.com/myshell-ai/OpenVoice |
| NVIDIA cuBLAS et cuDNN (composant NVIDIA) | NVIDIA | NVIDIA Software License (redistribution autorisée) | https://pypi.org/project/nvidia-cudnn-cu12/ |

Les modèles sont distribués tels que publiés par leurs auteurs, sans modification.
