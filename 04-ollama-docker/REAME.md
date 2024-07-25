Write the followings in the terminal.

<!-- ```bash
curl -fsSL https://ollama.com/install.sh | sh

ollama start
ollama pull phi3
ollama run phi3

pip install openai
```


Docker in CLI

```bash
docker run -it \
    -v ollama:/root/.ollama \
    -p 11434:11434 \
    --name ollama \
    ollama/ollama
```
Pulling the model
```bash
docker exec -it ollama bash
ollama pull phi3
``` -->

---
For writing the yaml
```bash
docker-compose up

jupyter-notebook

docker ps

docker exec -it ollama bash

olla pull phi3
```