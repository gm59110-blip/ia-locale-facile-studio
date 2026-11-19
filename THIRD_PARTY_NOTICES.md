# Composants tiers

IA Locale Facile Studio ne livre ni moteur ni modèle. L'installation télécharge ces éléments depuis leurs dépôts d'origine, et chacun reste sous sa propre licence.

## Moteurs et outils

| Composant | Licence | Source |
| --- | --- | --- |
| ComfyUI, lancé comme un programme séparé et non modifié | GPL-3.0 | https://github.com/Comfy-Org/ComfyUI |
| ComfyUI-GGUF | Apache 2.0 | https://github.com/city96/ComfyUI-GGUF |
| ComfyUI-AnimateDiff-Evolved | Apache 2.0 | https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved |
| llama.cpp | MIT | https://github.com/ggml-org/llama.cpp |
| PyTorch | BSD 3-Clause | https://github.com/pytorch/pytorch |

## Modèles proposés

| Modèle | Licence | Source |
| --- | --- | --- |
| FLUX.2 Klein 4B | Apache 2.0 | https://huggingface.co/Comfy-Org/Flux-2-Klein-4B |
| Z-Image Turbo | Apache 2.0 | https://huggingface.co/Comfy-Org/Z-Image-Turbo |
| Wan 2.2 TI2V 5B | Apache 2.0, avec des restrictions d'usage | https://huggingface.co/Wan-AI/Wan2.2-TI2V-5B |
| Hotshot-XL | CreativeML Open RAIL++-M, avec des restrictions d'usage | https://huggingface.co/hotshotco/Hotshot-XL |
| ControlNet Union SDXL | Apache 2.0 | https://huggingface.co/xinsir/controlnet-union-sdxl-1.0 |
| Real-ESRGAN | BSD 3-Clause | https://github.com/xinntao/Real-ESRGAN |
| Qwen 3 4B, traduction des prompts | Voir la page du modèle | https://huggingface.co/unsloth/Qwen3-4B-Instruct-2507-GGUF |

## Bibliothèques Python

FastAPI et Uvicorn (MIT ou BSD), httpx (BSD), websockets (BSD), Pillow (HPND), psutil (BSD), segno (BSD), PyAV (BSD), pywebview (BSD), uv (MIT ou Apache 2.0).

Les noms de modèles et de sociétés cités ici appartiennent à leurs détenteurs. Cette liste n'indique aucun partenariat.

## Assistant vocal (prévu pour une version suivante, désactivé dans cette version)

- Vosk et le modèle « vosk-model-small-fr-0.22 » : Apache 2.0, Alpha Cephei (https://alphacephei.com/vosk/models).
- faster-whisper : MIT, SYSTRAN ; modèle Whisper small : MIT, OpenAI (https://github.com/SYSTRAN/faster-whisper).
- Piper 2023.11.14-2 : MIT, Michael Hansen (https://github.com/rhasspy/piper), lancé comme programme séparé.
- Voix « fr_FR-mls-medium » de Piper : entraînée sur Multilingual LibriSpeech (OpenSLR 94), CC BY 4.0 (https://www.openslr.org/94/).
