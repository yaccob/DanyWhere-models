# DanyWhere models

Speech-recognition model files that [DanyWhere](https://github.com/yaccob/DanyWhere) downloads. They are **unmodified copies** of GGUF files published on Hugging Face by [handy-computer](https://huggingface.co/handy-computer) for [transcribe.cpp](https://github.com/handy-computer/transcribe.cpp) and [Handy](https://github.com/cjpais/Handy). They are mirrored here so DanyWhere also works on networks where Hugging Face is not reachable.

Each release holds one model at one Hugging Face revision; the tag is `<model id>-<first 12 characters of the revision>`. DanyWhere checks every downloaded file against the SHA-256 hash in its built-in catalog, so a file is only used if it matches the original byte for byte.

Every release includes the model's licence and notice files. The copyright of the models stays with their authors; this repository only redistributes them under their licences.

| Release | Model | Original | Licence |
| --- | --- | --- | --- |
| `whisper-large-v3-turbo-5eaf945c7978` | Whisper large-v3-turbo, Q8_0 | [openai/whisper-large-v3-turbo](https://huggingface.co/openai/whisper-large-v3-turbo), GGUF from [handy-computer/whisper-large-v3-turbo-gguf](https://huggingface.co/handy-computer/whisper-large-v3-turbo-gguf) | MIT (OpenAI) |

Not affiliated with OpenAI, NVIDIA, Hugging Face, handy-computer or Handy.
