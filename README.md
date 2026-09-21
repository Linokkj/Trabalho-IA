# Spotiflame • Buscador de Músicas & Tradutor via IA

**Disciplina:** Sistemas Inteligentes — Proz Educação  
**Professor:** Luciano Rocha  
**Integrantes:** [Seu Nome / Nome da Dupla]

---

## 🎯 Objetivo do Projeto
Aplicação web desenvolvida em PHP para buscar músicas a partir de um trecho da letra em inglês (via Genius API) e traduzir o trecho para o português utilizando modelos de Inteligência Artificial hospedados no Hugging Face.

---

## 🤖 Modelo(s) de IA Utilizado(s)
- **Modelo Principal:** [Musixmatch/opus-mt-en-romance](https://huggingface.co/Musixmatch/opus-mt-en-romance)[cite: 1]
- **Modelo Fallback:** [Helsinki-NLP/opus-mt-tc-big-en-pt](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-pt)[cite: 1]
- **Finalidade:** Tradução de texto (Inglês -> Português).
- **Tipo de Entrada:** Texto / String em inglês (ex: `>>por<< i found a love for me`)[cite: 1].
- **Tipo de Saída:** Array JSON com `translation_text`[cite: 1].

---

## 🛠️ Instruções de Configuração e Execução

1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/spotiflame.git](https://github.com/seu-usuario/spotiflame.git)
