# Licences et droits

Copilote vocal Star Citizen — créé par [Grumf81](https://github.com/Grumf81). Copyright © 2026 Plagnito.

**Projet de fan non officiel.** Mention demandée par CIG :

> This project is not endorsed by or affiliated with the Cloud Imperium or Roberts Space Industries group of
> companies. All game content and materials are copyright Cloud Imperium Rights LLC and Cloud Imperium Rights Ltd.
> Star Citizen®, Squadron 42®, Roberts Space Industries®, and Cloud Imperium® are registered trademarks of
> Cloud Imperium Rights LLC. All rights reserved.

En français : ce projet n'est ni approuvé par le groupe de sociétés Cloud Imperium ou Roberts Space Industries, ni
affilié à lui. Tout le contenu et le matériel du jeu sont protégés par le copyright de Cloud Imperium Rights LLC et de
Cloud Imperium Rights Ltd. Star Citizen®, Squadron 42®, Roberts Space Industries® et Cloud Imperium® sont des marques
déposées de Cloud Imperium Rights LLC. Tous droits réservés.

## Composants tiers inclus dans l'installateur

Chaque composant reste sous la licence de son auteur. Les textes complets sont sur les pages indiquées.

| Composant | Auteur | Licence | Source |
|---|---|---|---|
| Python 3.13 (python-build-standalone) | Python Software Foundation, Astral | PSF License | https://github.com/astral-sh/python-build-standalone |
| Bibliothèques Python (faster-whisper, vosk, sherpa-onnx, Flask…) | leurs auteurs respectifs | licences libres, voir chaque paquet dans `.venv\Lib\site-packages` | https://pypi.org/ |
| segno (QR code d'appairage du téléphone) | Lars Heuer | BSD 3-Clause | https://github.com/heuer/segno |
| uv | Astral | MIT / Apache 2.0 | https://github.com/astral-sh/uv |
| three.js (affichage 3D de l'avatar, avec son lecteur de fichiers FBX) | three.js authors | MIT | https://github.com/mrdoob/three.js |
| three-vrm (modèles VRM) | pixiv Inc. | MIT | https://github.com/pixiv/three-vrm |
| three-vrm-animation (animations VRM) | pixiv Inc. | MIT | https://github.com/pixiv/three-vrm |
| fflate (décompression des animations FBX) | Arjun Barrett | MIT | https://github.com/101arrowz/fflate |
| Modèles 3D d'Aria et de Chibi (avatar3d/aria.vrm, avatar3d/chibi.vrm) | Grumf81 | VRM Public License 1.0 : usage personnel non commercial, crédit de l'auteur requis | https://vrm.dev/licenses/1.0/ |
| Animations du corps d'Aria et de Chibi (avatar3d/animations/) | Mixamo (Adobe) | Utilisation libre selon les conditions de Mixamo | https://www.mixamo.com/ |
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
