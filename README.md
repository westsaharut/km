# Install Libraries

### Install UV

```sh {"id":"01J12M9GWY9J0KV8RAND9GXB19"}
uv venv
source .venv/bin/activate
```

```sh {"id":"01J12MB83HEJD6X51BHX49PSFN"}
# https://pypi.org/project/uv/
uv pip install llama-index-core
uv pip install llama-index-llms-openai
uv pip install llama-index-llms-replicate
uv pip install llama-index-embeddings-huggingface
```