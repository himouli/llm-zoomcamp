# Question 1. Running Ollama with Docker. What's the version? (1 point)
 0.1.48

# Question 2. Downloading an LLM. Manifest file (1 point)
root@ce5532af80ad:~/.ollama/models/manifests/registry.ollama.ai/library/gemma# cat 2b {"schemaVersion":2,"mediaType":"application/vnd.docker.distribution.manifest.v2+json",
"config":{"mediaType":"application/vnd.docker.container.image.v1+json","digest":"sha256:887433b89a901c156f7e6944442f3c9e57f3c55d6ed52042cbb7303aea994290","size":483},"layers"
:[{"mediaType":"application/vnd.ollama.image.model","digest":"sha256:c1864a5eb19305c40519da12cc543519e48a0697ecd30e15d5ac228644957d12","size":1678447520},
{"mediaType":"application/vnd.ollama.image.license","digest":"sha256:097a36493f718248845233af1d3fefe7a303f864fae13bc31a3a9704229378ca","size":8433},
{"mediaType":"application/vnd.ollama.image.template","digest":"sha256:109037bec39c0becc8221222ae23557559bc594290945a2c4221ab4f303b8871","size":136},
{"mediaType":"application/vnd.ollama.image.params","digest":"sha256:22a838ceb7fb22755a3b0ae9b4eadde629d19be1f651f73efb8c6b4e2cd0eea0","size":84}]}
root@ce5532af80ad:~/.ollama/models/manifests/registry.ollama.ai/library/gemma# 

# Question 3. Running the LLM. Output from 10 * 10 (1 point)
root@ce5532af80ad:~# ollama run gemma:2b >>> 10 * 10 Sure, here is the answer to your question:  10 * 10 = 100.

# Question 4. Downloading the weights. Size of the folder (1 point)
1.2 G

# Question 5. Adding the weights. Dockerfile (1 point )
./ollama_files /root/.ollama

# Question 6. Serving the LLM. Number of output tokens (1 point)
