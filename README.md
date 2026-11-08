# Prompt de vídeo

Guia visual: abra o `COMO-FUNCIONA.html` desta pasta (dois cliques; funciona sem internet).

Escreve o texto (prompt) para colar numa ferramenta de gerar vídeo com IA: prompt por tomada, variações de movimento e, para avatar falante, a fala completa. Antes, confere na documentação atual o que a ferramenta aceita. Não gera o vídeo.

## Como instalar

**Direto do GitHub:** no Claude Code, diga: "Instale a skill a partir de https://github.com/Empire-Business/omnx-video-criar-prompt". Para atualizar, diga: "Atualize a skill a partir de https://github.com/Empire-Business/omnx-video-criar-prompt". A IA baixa e copia os arquivos.

Se você já baixou esta pasta:

1. Abra o Claude Code (aplicativo do Claude, aba **Code**, ambiente **Local**).
2. Escreva: **"Instale a skill omnx-video-criar-prompt a partir desta pasta: `<caminho desta pasta>`"**.
3. A IA copia a skill para o lugar certo. Você não digita comando nenhum e vê um aviso de que terminou.
4. Abra uma conversa nova e peça, por exemplo: **"Cria um prompt de vídeo de 8 segundos do meu perfume em cima de uma pedra molhada."**.

### Instalar à mão

- **Mac ou Linux:** rode `bash install.sh` nesta pasta (dá para rodar de qualquer lugar, com o caminho entre aspas). A skill vai para `~/.claude/skills/omnx-video-criar-prompt`. Se editar algo aqui, rode de novo.
- **Windows:** copie esta pasta, sem o `install.sh`, para `%USERPROFILE%\.claude\skills\omnx-video-criar-prompt`. Ou peça para a IA fazer isso.

## O que ela não faz

- Não gera o vídeo.
- Não cria avatar que se passe por cliente ou especialista, nem depoimento gerado por IA.
- VSL é do Otto; editar gravação, do Cortez; roteiro de Reels gravado por gente, da Cami.

## Pedidos que funcionam

- "Cria um prompt de vídeo de 8 segundos do meu perfume em cima de uma pedra molhada."
- "Transforma essa foto em vídeo com um movimento leve."
- "Escreve o roteiro de um avatar falante para dar boas-vindas aos alunos."
- "Preciso de um comercial curto do meu produto gerado por IA."

## Outro sistema operacional e outra ferramenta

Funciona em Mac, Windows e Linux, no Claude Code e no Codex. Na instalação, a própria IA faz as adaptações necessárias para o seu computador.
