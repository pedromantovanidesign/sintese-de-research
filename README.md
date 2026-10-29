# síntese de research

Cruza transcrições de entrevista, agrupa padrões e devolve os temas com a evidência literal de cada um.

Uma skill para o [Claude Code](https://claude.com/claude-code). Não é um script: é **critério de trabalho escrito por extenso**, para que a decisão seja a mesma na segunda-feira e na sexta.

## Por que ela existe

Doze entrevistas de uma hora são cem páginas de transcrição. Ler tudo leva dias, e quando termina a primeira já saiu da cabeça. O que acontece na prática é pior: a síntese sai da memória das três últimas conversas.

Esta skill lê todas e devolve os temas com a frase literal que sustenta cada um. Ela não conclui nada: organiza o material para que a conclusão seja tomada olhando a evidência inteira.

## O método, com crédito

O procedimento segue a **análise temática** de **Virginia Braun e Victoria Clarke**, *Using thematic analysis in psychology*, Qualitative Research in Psychology, 2006.

🔴 **O método é público e tem autor. O que é próprio é a disciplina de rodar sempre, e o critério de corte.**

## O que ela devolve

Os temas por força, cada um com nome em frase e citações literais. Mais: os sinais isolados, as contradições, o que este material não responde, e as perguntas para a próxima rodada.

## O que ela NÃO faz

Organiza, não conclui. Enxerga só o que foi perguntado, e a ausência de um assunto não quer dizer nada. Transcrição automática erra em nome e número, então citação decisiva se confere no áudio. E quem recrutou define o que vai sair: se as doze pessoas vieram da mesma lista, os temas são daquela lista.

## O que tem aqui

```
SKILL.md    a skill inteira, que é o que o Claude lê
README.md   este arquivo
LICENSE     MIT
```

## Instalar

```bash
git clone https://github.com/pedromantovanidesign/sintese-de-research.git ~/.claude/skills/sintese-de-research
```

O Claude Code carrega a skill sozinho quando o assunto aparece, ou com `/sintese-de-research`.

---

Escrito e mantido por [Pedro Mantovani](https://pedromantovani.com) · Product & Brand Designer
