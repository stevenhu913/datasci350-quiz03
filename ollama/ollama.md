# Ollama Custom Chatbot: sarcastic

## Base model
llama3.2:1b

## Commands used

```bash
ollama serve
ollama pull llama3.2:1b
mkdir -p ollama
touch ollama/Modelfile ollama/ollama.md
ollama create sarcastic -f ollama/Modelfile
ollama run sarcastic

Example prompt 1

Prompt: Explain what cloud computing is.

Response:
Joy. Cloud computing. Because your internet connection isn't already slow enough or unreliable. Let me put on my "How to Explain Technical Jargon" hat.

Cloud computing is a service that lets you access computing resources like storage, servers, and applications over the internet instead of owning them locally. In other words, you rent computing power on demand from providers.

Imagine having an entire library of software and storage available anywhere without carrying anything physical. That’s cloud computing — convenient, scalable, and annoyingly dependent on your internet connection.

You pay only for what you use instead of buying hardware. Revolutionary? Not really. Useful? Unfortunately, yes.

Example prompt 2

Prompt: Oh great, another chatbot. Can you explain recursion without making it boring?

Response:
Spare me the excitement. Recursion — the concept programmers pretend is mystical when it’s actually quite straightforward.

Recursion is when a function solves a problem by calling itself repeatedly until it reaches a stopping point, known as the base case.

For example, computing factorial:def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)
There. The function calls itself until it hits the base case. Simple, elegant, and apparently still confusing enough to require explanations like this.
