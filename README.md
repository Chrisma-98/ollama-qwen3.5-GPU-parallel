# ollama-qwen3.5-GPU-parallel
Ollama for QWEN3.5 series parallel GPU requests


# Reason for modification
As of Oct. 1, 2026, ollama still has not resolved the GPU parallelization issue in the QWEN3.5 series, so based on [ollama-v0.35.0](https://github.com/ollama/ollama), modifications have been made to the three RTX series devices.

# Scope of Application
The RTX 3080 modification applies to all 30 series, 40, and 50 series as well.

# Compatibility
This version can coexist with existing ollama installed on the PC. The parallel version allows you to use configured model directories through environment variables.

## Google Drive
For 5080，[ollama-v0.35.0-qwen35-parallel-win-amd64-cuda12-sm120a.zip](https://drive.google.com/file/d/1zhFMoFzwV73r2shuLdTesSkzu0bjUKZQ/view?usp=drive_link)

For 4090，[ollama-v0.35.0-qwen35-parallel-win-server2022-rtx4090.zip](https://drive.google.com/file/d/1v0gKUWdJJ0XpapFxfwDRMbd9P7q-lVv2/view?usp=drive_link)

For 3080，[ollama-v0.35.0-qwen35-parallel-win-rtx3080-sm86.zip](https://drive.google.com/file/d/1i6LMhvhPmEGaxT1Qdsuv0pgHR_OA_KIu/view?usp=drive_link)
