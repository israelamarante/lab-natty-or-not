# 🤖 Natural ou Fake Natty? — IA e o Futuro do Trabalho

**Autor:** Israel Amarante — [github.com/israelamarante](https://github.com/israelamarante)  
**Projeto:** #LabDIONattyOrNot

---

## Introdução
Este repositório contém um projeto demonstrativo feito com IAs Generativas: e-book, roteiro de vídeo e imagem de capa. O objetivo é mostrar como *trabalhar com* IA para criar valor no mercado de trabalho.

## Conteúdo do projeto
- `assets/ebook-profissional-hibrido.pdf` — Mini e-book em PDF.
- `assets/capa-ia-futuro-trabalho.png` — Imagem de capa (substitua pela versão gerada por DALL·E ou outra ferramenta).
- `assets/roteiro-video.md` — Roteiro do vídeo com narração.
- `video-link.txt` — Coloque aqui a URL do vídeo (YouTube) após o upload.

## Como usar (resumo)
1. Abra o README e veja o e-book em `assets/`.
2. Substitua a imagem de capa (`assets/capa-ia-futuro-trabalho.png`) pela imagem final gerada por IA.
3. Gere a narração (opcional) e monte o vídeo. Suba no YouTube e atualize `video-link.txt`.

![Capa IA Futuro do Trabalho](./assets/capa-ia-futuro-trabalho.png)

---
## Como publicar no GitHub (passo a passo para iniciantes)

### Opção A — Usando o GitHub Web (mais simples)
1. Acesse https://github.com/new e crie um novo repositório chamado `natural-or-fake-natty` (ou outro nome que preferir).
2. No repositório criado, clique em **Upload files**.
3. Arraste a pasta `assets` e o arquivo `README.md` para a área de upload e clique em **Commit changes**.
4. Pronto — o README será exibido automaticamente.

### Opção B — Usando Git no terminal (recomendado se quiser aprender)
1. Instale o Git: https://git-scm.com/downloads
2. Abra o terminal (Git Bash no Windows) e navegue até a pasta do projeto:
   ```bash
   cd caminho/para/natural-or-fake-natty-v2
   ```
3. Inicialize o repositório, adicione arquivos e envie para o GitHub (substitua a URL pelo seu repositório HTTPS ou SSH):
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Natural or Fake Natty by Israel Amarante"
   git branch -M main
   git remote add origin https://github.com/israelamarante/natural-or-fake-natty.git
   git push -u origin main
   ```
   > Se usar HTTPS, ao pedir credenciais, gere um Personal Access Token no GitHub (Settings → Developer settings → Personal access tokens) e use-o como senha.

---
## Créditos e ferramentas usadas
- Textos gerados com ChatGPT (GPT-5)
- Imagem de capa: gerada por IA (DALL·E 3 / alternativas)
- Narração: ElevenLabs (opcional)
- Montagem: CapCut, Runway ML ou similar
