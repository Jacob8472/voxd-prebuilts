# voxd-prebuilts
This repository hosts prebuilt dependencies for voxd app.  

Prebuilt CPU-only binaries for:
- whisper.cpp → `whisper-cli`
- llama.cpp → `llama-server`
- ydotool → `ydotool` (client) and `ydotoold` (daemon)

These artifacts are built from upstream sources and published under their original licenses.  
No model weights are included (the respective models are fetched by voxd from their respective repositories).

Latest release assets:
- `whisper-cli_linux_amd64_avx2.tar.gz`
- `whisper-cli_linux_amd64_sse4.2.tar.gz`
- `whisper-cli_linux_arm64.tar.gz`
- `llama-server_linux_amd64_avx2.tar.gz`
- `llama-server_linux_amd64_sse4.2.tar.gz`
- `llama-server_linux_arm64.tar.gz`
- `ydotool_linux_amd64.tar.gz`
- `ydotoold_linux_amd64.tar.gz`
- `ydotool_linux_arm64.tar.gz`
- `ydotoold_linux_arm64.tar.gz`
- `SHA256SUMS_*.txt`

Direct URL (to latest builds): [Releases](https://github.com/jakovius/voxd-prebuilts/releases/latest)
