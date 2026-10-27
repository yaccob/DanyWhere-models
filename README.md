# DanyWhere models

Speech-recognition model files that [DanyWhere](https://github.com/yaccob/DanyWhere) downloads. They are **unmodified copies** of GGUF files published on Hugging Face by [handy-computer](https://huggingface.co/handy-computer) for [transcribe.cpp](https://github.com/handy-computer/transcribe.cpp) and [Handy](https://github.com/cjpais/Handy). They are mirrored here so DanyWhere also works on networks where Hugging Face is not reachable.

Each release holds one model at one Hugging Face revision; the tag is `<model id>-<first 12 characters of the revision>`. DanyWhere checks every downloaded file against the SHA-256 hash in its built-in catalog, so a file is only used if it matches the original byte for byte.

Every release includes the model's licence and notice files. The copyright of the models stays with their authors; this repository only redistributes them under their licences.

| Release | Model | Original | Licence |
| --- | --- | --- | --- |
| `whisper-large-v3-turbo-5eaf945c7978` | Whisper large-v3-turbo, Q8_0 | [openai/whisper-large-v3-turbo](https://huggingface.co/openai/whisper-large-v3-turbo), GGUF from [handy-computer/whisper-large-v3-turbo-gguf](https://huggingface.co/handy-computer/whisper-large-v3-turbo-gguf) | MIT (OpenAI) |
| `parakeet-tdt-0.6b-v3-85ac09ea12fc` | Parakeet TDT 0.6B v3, Q8_0 | [nvidia/parakeet-tdt-0.6b-v3](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3), GGUF from [handy-computer/parakeet-tdt-0.6b-v3-gguf](https://huggingface.co/handy-computer/parakeet-tdt-0.6b-v3-gguf) | CC BY 4.0 (NVIDIA) |
| `whisper-medium-ec78f06fded5` | Whisper medium, Q8_0 | [openai/whisper-medium](https://huggingface.co/openai/whisper-medium), GGUF from [handy-computer/whisper-medium-gguf](https://huggingface.co/handy-computer/whisper-medium-gguf) | MIT (OpenAI) |
| `whisper-small-c0214bd34be9` | Whisper small, Q8_0 | [openai/whisper-small](https://huggingface.co/openai/whisper-small), GGUF from [handy-computer/whisper-small-gguf](https://huggingface.co/handy-computer/whisper-small-gguf) | MIT (OpenAI) |
| `parakeet-unified-en-0.6b-7e948f21b7bd` | Parakeet Unified English 0.6B, Q8_0 | [nvidia/parakeet-unified-en-0.6b](https://huggingface.co/nvidia/parakeet-unified-en-0.6b), GGUF from [handy-computer/parakeet-unified-en-0.6b-gguf](https://huggingface.co/handy-computer/parakeet-unified-en-0.6b-gguf) | NVIDIA Open Model License |
| `canary-180m-flash-46b86384d1db` | Canary 180M Flash, Q8_0 | [nvidia/canary-180m-flash](https://huggingface.co/nvidia/canary-180m-flash), GGUF from [handy-computer/canary-180m-flash-gguf](https://huggingface.co/handy-computer/canary-180m-flash-gguf) | CC BY 4.0 (NVIDIA) |

Not affiliated with OpenAI, NVIDIA, Hugging Face, handy-computer or Handy.
