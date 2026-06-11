# Plano de Curso — Engenharia de Conhecimento da IA (v2)

> Formato **INEMA.CLUB** · 6 trilhas (1 por camada da Pirâmide da Inteligência Aplicada) · **muito conteúdo, muita prática, muitos exemplos** · eixo dedicado a **quem está entrando tarde** · motor de **marketing viral** embutido · **Prova da Pirâmide** no final, com correção instantânea e badge compartilhável.

---

## 0. Posicionamento e nomes

**Nome do framework (autoridade):** Engenharia de Conhecimento da IA — Pirâmide da Inteligência Aplicada.

**Nome de venda (o que para o scroll):**

> **A Pirâmide da IA — você não precisa de 100 prompts. Precisa de 6 camadas.**

Sub-promessas alternativas para testes A/B:
- "Entrou tarde na IA? A pirâmide que transforma atraso em vantagem."
- "Pare de colecionar prompts. Comece a construir inteligência."
- "Do zero ao sistema que aprende com você — em 6 camadas."

**Posicionamento contra o mercado:** todo curso de IA em PT-BR vende lista de prompts. Este vende **estrutura** — e ataca de frente a barreira emocional ("já estou atrasado") que nenhum concorrente toca.

| # | Camada | Trilha | Cor | Frase-âncora | Caso-âncora exclusivo |
|---|--------|--------|-----|--------------|----------------------|
| 1 | **Prompt** | T1 | Emerald 🟢 | "Prompt é a pergunta." | O e-mail difícil: mesmo pedido, 4 versões, 4 resultados |
| 2 | **Intenção** | T2 | Blue 🔵 | "Intenção é o destino." | O post que vendeu zero: prompt perfeito, alvo errado |
| 3 | **Contexto** | T3 | Purple 🟣 | "Contexto é o mapa." | A campanha genérica: a IA não era fraca, estava cega |
| 4 | **Aproveitamento** | T4 | Amber 🟡 | "Aproveitamento é o método." | O acerto que se perdeu: ninguém anotou por que funcionou |
| 5 | **Arquitetura** | T5 | Teal 🟦 | "Arquitetura é o sistema." | O gargalo invisível: 10 prompts bons, processo quebrado |
| 6 | **Evolução** | T6 | Rose 🌹 | "Evolução é o aprendizado acumulado." | O vídeo que bombou (e o canal que não aprendeu nada com ele) |

> **Regra anti-repetição:** cada trilha abre com seu caso-âncora — uma situação onde **só aquela camada** resolve. O aluno nunca sente "isso é igual à trilha anterior". O caso abre o index da trilha e é retomado nos módulos.

---

## 1. O eixo "Quem entra tarde" (diferencial do curso)

Atravessa TODAS as trilhas. Quatro mecanismos:

1. **Diagnóstico de nível** (landing + início de cada trilha): 6 perguntas → "seu ponto real na pirâmide é a camada X". Combate o erro do relatório §10 (entrar no meio sem fundamento). **É também o motor viral** — ver §11.
2. **Box "Atalho do retardatário"** em cada módulo: versão mínima viável da camada, 1 template pronto + 1 exercício de 10 min.
3. **Módulo 1.0 Base Zero** pra quem nunca usou IA — inclui **verificação** (usar sem se queimar).
4. **Box "Na sua profissão"** em cada trilha: o caso traduzido pra 5 perfis — **professor, advogado, vendedor, gestor, autônomo/criador**. Requalificação = mercado de trabalho; o aluno se vê no exemplo.

Mantra: **"Você não está atrasado. Você está começando pela base — que é exatamente onde se deve começar."**

---

## 2. Estrutura geral

```
engenharia-conhecimento-ia/
├── index.html                      # Landing: pirâmide interativa + diagnóstico viral + 6 trilhas
└── curso/
    ├── trilha1/  (Prompt — Emerald)        modulo-1-0, 1-1, 1-2
    ├── trilha2/  (Intenção — Blue)          modulo-2-1, 2-2
    ├── trilha3/  (Contexto — Purple)        modulo-3-1, 3-2
    ├── trilha4/  (Aproveitamento — Amber)   modulo-4-1, 4-2
    ├── trilha5/  (Arquitetura — Teal)       modulo-5-1, 5-2
    ├── trilha6/  (Evolução — Rose)          modulo-6-1, 6-2
    └── prova/
        └── index.html              # Prova da Pirâmide: 12 questões + gabarito comentado + badge
```

Padrão por módulo: **6–8 tópicos**, 500–800 linhas, ≥1 SVG futurista, variedade de componentes (grids ✓/✗, timeline, tip boxes, prompt boxes), **≥3 exemplos práticos copy-paste por módulo**, **entregável** ao final.

Total: **13 módulos + prova final**. Carga: ~12–15h.

---

## 3. Trilha 1 — Engenharia de Prompt (Emerald) 🟢

**Caso-âncora:** *O e-mail difícil.* Você precisa responder um cliente insatisfeito. Mesmo pedido em 4 versões — do "responde esse cliente" ao prompt completo com papel, tom, formato e exemplo. As 4 respostas lado a lado. O aluno VÊ a diferença antes de aprender a teoria.
**Pergunta-guia:** *Como pedir melhor?*

### Módulo 1.0 — Base Zero (pra quem entra agora)
1. O que é IA generativa, em 1 frase honesta (sem hype)
2. Modelo, prompt, resposta, janela de contexto — vocabulário mínimo
3. Como abrir e conversar (ChatGPT / Claude / Gemini — onde clicar)
4. Os 3 mitos do retardatário ("é tarde", "é só pra programador", "vai me substituir")
5. Primeira conversa guiada (copie, cole, veja acontecer)
6. **Verificação: use sem se queimar** — o que é alucinação, os 3 cheques antes de usar qualquer resposta (fonte? data? faz sentido?), quando a IA inventa com confiança
7. O que a IA NÃO faz bem (e por que saber isso te protege)

**Prática:** primeira conversa funcional + caçar 1 alucinação de propósito ("me dê 5 fatos sobre [tema que você domina]" e conferir).
**Entregável:** print do antes/depois + checklist de verificação preenchido.

### Módulo 1.1 — Anatomia de um bom prompt
1. As 5 partes: Papel · Tarefa · Contexto · Formato · Exemplo
2. Pedido fraco × forte (grid ✓/✗ — exemplos do relatório §3 + caso do e-mail)
3. Definir formato de saída (lista, tabela, passo a passo)
4. Pedir o nível certo de explicação (criança / leigo / especialista)
5. Pedir exemplos e comparações de propósito
6. Erros que matam o prompt: genérico, ambíguo, sem formato
7. Iteração: melhorar a resposta sem recomeçar do zero

**Prática:** o mesmo prompt em 3 níveis de explicação; consertar 5 prompts quebrados (exercício com gabarito).
**Entregável:** 3 prompts ruins seus transformados em fortes (ficha).

### Módulo 1.2 — Prompts reutilizáveis
1. Por que reescrever sempre é desperdício
2. Anatomia de template com variáveis `[ ]`
3. **10 templates prontos**: resumo, e-mail, explicação, brainstorm, revisão, comparação, plano de aula, proposta comercial, post, análise de documento
4. Onde guardar (doc, notas, biblioteca pessoal)
5. Nomear e versionar
6. **Atalho do retardatário:** os 3 templates que resolvem 80% do dia
7. **Na sua profissão:** o template-chave de cada perfil (professor: plano de aula · advogado: análise de cláusula · vendedor: follow-up · gestor: resumo de reunião · criador: roteiro)

**Entregável:** **biblioteca pessoal de 5+ prompts** nomeados, salva.

> **Kit T1** — Template universal:
> ```
> Você é [PAPEL]. Sua tarefa é [TAREFA].
> Contexto: [O QUE A IA PRECISA SABER].
> Formato: [LISTA/TABELA/PASSOS]. Restrições: [O QUE EVITAR].
> Exemplo do que quero: [1 EXEMPLO].
> Antes de responder, diga o que assumiu.
> ```

---

## 4. Trilha 2 — Engenharia de Intenção (Blue) 🔵

**Caso-âncora:** *O post que vendeu zero.* Prompt tecnicamente perfeito, texto bonito — e nenhuma venda. O prompt pedia "um texto sobre o produto"; a intenção real era "fazer o leitor agendar uma conversa". A IA acertou a tarefa e errou o destino. Só intenção resolve isso — prompt melhor não resolveria.
**Pergunta-guia:** *Para que estou pedindo isso?*

### Módulo 2.1 — Tarefa × Intenção
1. A diferença entre o que peço e o que quero alcançar
2. As 6 perguntas da intenção: objetivo, transformação, decisão, público, efeito, motivo
3. Dissecando o caso: o mesmo post com 3 intenções diferentes (informar / vender / autoridade) — 3 textos completamente distintos
4. O custo de responder bem pro alvo errado
5. Como declarar intenção dentro do prompt
6. Quando a intenção muda a resposta inteira (3 estudos rápidos)
7. Checklist de intenção antes de apertar enter

**Prática:** pegar 1 texto que você já pediu pra IA e regerar com 2 intenções opostas; comparar.
**Entregável:** pedido real reescrito declarando público + objetivo + efeito.

### Módulo 2.2 — Intenção aplicada a resultado
1. Intenção em conteúdo (o que o vídeo/post deve CAUSAR)
2. Intenção em vendas (a decisão que o leitor precisa tomar)
3. Intenção em decisão/gestão (que escolha isso destrava)
4. Intenção em atendimento (resolver, não só responder)
5. Alinhar tom e linguagem à intenção
6. **Atalho do retardatário:** a frase de 1 linha "meu objetivo real aqui é ___"
7. **Na sua profissão:** professor (a aula deve fazer o aluno conseguir o quê?) · advogado (o parecer sustenta qual decisão?) · vendedor (qual o próximo passo do lead?) · gestor (qual decisão a análise habilita?) · criador (o que o público faz após assistir?)

**Entregável:** **carta de intenção** reutilizável do seu trabalho.

> **Kit T2** — Bloco de intenção (cola antes do prompt):
> ```
> Objetivo final: [...]. Público: [...]. Efeito/decisão que quero gerar: [...].
> Se precisar escolher, priorize: [clareza | persuasão | precisão | velocidade].
> ```

---

## 5. Trilha 3 — Engenharia de Contexto (Purple) 🟣

**Caso-âncora:** *A campanha genérica.* "Crie uma campanha pro meu projeto" → resultado que serviria pra qualquer empresa do planeta. A IA não era fraca: estava **cega**. Mesmo prompt + pasta de contexto (público, exemplos que funcionaram, tom da marca, limites) → campanha que parece feita por quem trabalha lá há anos. Nem prompt nem intenção resolvem cegueira — só contexto.
**Pergunta-guia:** *O que a IA precisa saber pra entender melhor?*

### Módulo 3.1 — O que é contexto (além do prompt)
1. Contexto = mapa: respostas ruins quase sempre são contexto pobre
2. Os tipos: arquivos, imagens, docs, histórico, exemplos bons/ruins, regras, marca, público, restrições
3. Anexar arquivos e referências (como cada ferramenta lida)
4. Exemplos positivos e negativos como contexto ("assim sim, assim não")
5. Identidade de marca/voz como contexto reutilizável
6. Quando contexto demais atrapalha (ruído × sinal)
7. **Privacidade e dados: o que NUNCA colar na IA** — dados de clientes, senhas, contratos confidenciais, dados de saúde; como anonimizar antes de usar ([NOME], [EMPRESA]); o que cada ferramenta faz com seus dados; a regra de ouro: "colaria isso num grupo público?"

**Prática:** anonimizar um documento real e usá-lo como contexto; comparar resposta com e sem a pasta de contexto.
**Entregável:** **pasta de contexto** do seu projeto + checklist de privacidade.

### Módulo 3.2 — Engenharia de contexto na prática
1. O "briefing permanente": doc que você cola/reanexa sempre
2. Estrutura de pastas que a IA entende
3. Transformar histórico de conversas em contexto reaproveitável
4. Dossiê de público-alvo (1 página que melhora tudo)
5. Restrições e regras internas como guarda-corpo
6. **Atalho do retardatário:** o mini-briefing de 5 linhas
7. **Na sua profissão:** professor (perfil da turma + currículo) · advogado (modelos da banca + jurisprudência usual) · vendedor (ICP + objeções frequentes) · gestor (metas + restrições do trimestre) · criador (nicho + 3 posts que performaram)

**Entregável:** **briefing-base do projeto** pronto pra reanexar.

> **Kit T3** — Briefing-base:
> ```
> # Projeto: [nome]
> Quem somos / voz: [...] · Público: [...]
> Exemplos bons: [...] · Exemplos a evitar: [...]
> Regras/limites: [...] · Resultado esperado: [...]
> ⚠ Dados sensíveis: anonimizados (checklist ok)
> ```

---

## 6. Trilha 4 — Engenharia de Aproveitamento (Amber) 🟡

**Caso-âncora:** *O acerto que se perdeu.* Um post performou 10× a média. Três meses depois, ninguém lembra qual era a estrutura, o prompt, o gancho. O conhecimento existiu — e evaporou. Prompt, intenção e contexto estavam certos; faltou **registrar e transformar em método**.
**Pergunta-guia:** *O que deu certo e pode virar método?*

### Módulo 4.1 — Da tentativa ao padrão
1. Por que conhecimento não registrado se perde (o caso, dissecado)
2. O que registrar: prompts que funcionaram, respostas boas, erros recorrentes
3. Achar a estrutura por trás do acerto (Dor→Explicação→Exemplo→Benefício→CTA, relatório §6)
4. Acerto → template · erro → ajuste · repetição → processo
5. Seu primeiro **playbook** (1 página por processo)
6. Métricas simples: o que conta como "deu certo"
7. Rotina de captura: 5 min no fim do dia

**Prática:** fazer engenharia reversa de 1 conteúdo seu (ou de referência) que performou — extrair a estrutura em 5 passos.
**Entregável:** **1 playbook** de um processo seu.

### Módulo 4.2 — Biblioteca viva
1. Organizar: prompts, briefings, playbooks num lugar só
2. Nomeação e versão (v1, v2, "campeão atual")
3. Checklists a partir de processos repetidos
4. Curadoria: aposentar o que parou de funcionar
5. Compartilhar com equipe / clientes (seu método vira ativo)
6. **Atalho do retardatário:** registre só os 3 prompts que mais usa
7. **Na sua profissão:** professor (banco de planos por turma) · advogado (banco de teses e modelos) · vendedor (playbook de objeções) · gestor (decisões registradas + critérios) · criador (estruturas campeãs por formato)

**Entregável:** **índice da biblioteca pessoal**.

> **Kit T4** — Ficha de aproveitamento:
> ```
> O que tentei: [...] · Funcionou? [sim/não] · Por quê: [...]
> Vira template? [...] · Vira regra? [...] · Onde guardei: [...]
> ```

---

## 7. Trilha 5 — Engenharia de Arquitetura (Teal) 🟦

**Caso-âncora:** *O gargalo invisível.* Dez prompts excelentes, biblioteca organizada — e o trabalho ainda trava, porque cada etapa depende de você lembrar de fazer. O problema não é nenhum prompt: é que **não existe processo conectando as peças**. Só arquitetura resolve.
**Pergunta-guia:** *Como organizar tudo num sistema funcional?*
**⚠ Regra da trilha:** 100% no-code/conceitual. Nada de ferramenta técnica obrigatória — fluxos desenháveis em papel e executáveis em qualquer chat de IA.

### Módulo 5.1 — Pensar em sistemas, não em comandos
1. De comando isolado a fluxo (entrada→interpretação→ação→avaliação→ajuste→nova ação, §7)
2. O que a IA faz num sistema: interpretar, organizar, sugerir, revisar, comparar, executar partes
3. Desenhar seu primeiro fluxo (produção de conteúdo, §7, passo a passo)
4. Pontos de decisão e ramificações
5. Onde o humano entra (handoff humano × IA)
6. A lógica do loop: Pensar→Agir→Avaliar→Ajustar→Agir (§9)
7. Visão geral de ferramentas (no-code, agentes) — o suficiente pra não se intimidar, sem dependência

**Prática:** desenhar o fluxo do caso-âncora e marcar onde ele quebrava.
**Entregável:** **fluxograma de 1 processo seu** (papéis IA/humano marcados).

### Módulo 5.2 — Montando um mini-sistema
1. Do fluxo no papel ao fluxo executável (num simples chat)
2. Encadear prompts (saída de um vira entrada do outro) — exemplo completo de 4 etapas
3. Bases de conhecimento como peça do sistema
4. Loop de revisão (a IA avalia o próprio resultado com critérios seus)
5. Critérios de qualidade dentro do fluxo
6. **Atalho do retardatário:** o sistema mínimo de 3 caixas que já entrega valor
7. **Na sua profissão:** professor (fluxo de criação de aula) · advogado (fluxo de análise de contrato) · vendedor (fluxo lead→proposta) · gestor (fluxo de decisão semanal) · criador (fluxo ideia→post publicado)

**Prática:** executar o mini-sistema de 3 caixas com um caso real, do início ao fim.
**Entregável:** **1 mini-sistema documentado** (fluxo + prompts de cada etapa).

> **Kit T5** — Esqueleto de fluxo:
> ```
> [Entrada] → [IA interpreta] → [IA gera proposta] → [Avaliação: critérios X]
>   → ok: [entrega] · não ok: [ajusta] → volta à geração
> ```

---

## 8. Trilha 6 — Engenharia de Evolução (Rose) 🌹

**Caso-âncora:** *O vídeo que bombou (e o canal que não aprendeu nada).* Um vídeo fez 50× a média. O criador comemorou — e o canal seguiu igual. Seis meses depois, ninguém sabe replicar. Sistema rodando não é sistema evoluindo: faltou o ciclo que transforma resultado em aprendizado.
**Pergunta-guia:** *Como o sistema melhora com o tempo?*

### Módulo 6.1 — O ciclo que aprende
1. Comemorar não basta — extrair o porquê
2. As 8 perguntas pós-resultado (tema, título, imagem, promessa, estrutura, comentários, repetir, ajustar — §8)
3. Feedback como combustível: cliente, dados, erro
4. Fechar o loop: aprendizado vira input do próximo ciclo
5. Refinamento contínuo de prompts/briefings/playbooks
6. Histórico de decisões como ativo
7. Sinais de que o sistema evolui de verdade (vs. só roda)

**Prática:** aplicar as 8 perguntas a 1 trabalho recente seu.
**Entregável:** **1 retrô** com 3 melhorias pro próximo ciclo.

### Módulo 6.2 — Inteligência operacional acumulada (capstone)
1. Juntar tudo: prompts + intenção + contexto + métodos + arquitetura + evolução
2. Ritmo de revisão (semanal/mensal) sem burocracia
3. Métricas que importam pro SEU objetivo
4. Quando reescrever o sistema vs. ajustar
5. Vantagem composta: por que em 6 meses o "atrasado" ultrapassa quem só coleciona prompts
6. **Capstone como portfólio:** montar o "mapa do seu sistema de conhecimento de IA" (1 página) E **como apresentá-lo** — post de LinkedIn pronto pra adaptar, como descrever no currículo, como explicar numa entrevista ("eu não uso IA, eu opero um sistema de IA")
7. **Atalho do retardatário:** a pergunta única "o que repito que poderia ser melhor?"

**Entregável-mãe:** **Mapa do Sistema de Conhecimento de IA** (peça de portfólio) + post de LinkedIn adaptável.

> **Kit T6** — Ritual de evolução (pós-entrega):
> ```
> Funcionou: [...] · Por quê: [...]
> Ajustar: [...] · Vira regra nova? [...]
> Próximo ciclo começa com: [...]
> ```

---

## 9. Prova da Pirâmide (curso/prova/index.html) 🏆

**Princípio:** fácil de realizar (pra pessoa E pra gente construir) e **a correção ensina** — quando a pessoa vê a resposta, ela entende na hora.

### Formato
- **12 questões** de múltipla escolha — 2 por camada, em ordem da pirâmide.
- Cada questão é um **mini-caso prático** ("Maria pediu X e recebeu Y genérico. Qual camada falhou?"), nunca decoreba.
- **Correção instantânea, questão a questão**: clicou → vê na hora se acertou + **gabarito comentado** (por que a certa é certa E por que cada errada é errada). Errar também ensina.
- 100% client-side (HTML+JS, padrão INEMA) — sem cadastro, sem backend, roda no GitHub Pages.

### Resultado = badge compartilhável (motor viral nº 2)
- 0–4: **Explorador da Base** 🟢 · 5–8: **Construtor de Contexto** 🟣 · 9–11: **Arquiteto de Sistemas** 🟦 · 12: **Engenheiro de Evolução** 🌹
- Card visual com nível + pirâmide colorida até a camada alcançada + frase pronta: *"Tirei [nível] na Prova da Pirâmide da IA. Em qual camada você está? 👉 [link]"*
- Botão "copiar resultado" + link pra trilha recomendada conforme os erros ("você errou as 2 de contexto → comece pela T3").

### Exemplo de questão (modelo)
> **Q7.** João tem 30 prompts excelentes salvos, mas toda semana esquece etapas do processo de criar a newsletter. Qual camada resolve?
> a) Prompt — escrever prompts melhores
> b) Contexto — anexar mais arquivos
> c) **Arquitetura — conectar as etapas num fluxo** ✅
> d) Evolução — analisar resultados passados
>
> **Gabarito comentado:** os prompts já são bons (não é a) e a IA já entende o assunto (não é b). O problema é que as peças não estão conectadas num processo — exatamente o papel da Arquitetura. Evolução (d) viria depois: só se melhora um processo que existe.

---

## 10. Fio condutor "pronto pra usar"

| Camada | Artefato que sai pronto |
|--------|-------------------------|
| Prompt | Biblioteca de prompts + checklist de verificação |
| Intenção | Carta de intenção reutilizável |
| Contexto | Briefing-base + checklist de privacidade |
| Aproveitamento | Playbook + índice da biblioteca |
| Arquitetura | Fluxo + mini-sistema documentado |
| Evolução | **Mapa do sistema (portfólio) + post LinkedIn + ritual** |

Entrega-mãe: o **Sistema de Conhecimento de IA pessoal** — mostrável em entrevista, LinkedIn e proposta de serviço.

---

## 11. Plano de marketing viral 📣

### Motor 1 — Diagnóstico de nível (landing)
- 6 perguntas, 1 por camada, respondíveis em 60s.
- Resultado: "Você está na camada X/6" + pirâmide colorida até o nível + card compartilhável: *"Estou no nível [X] da Pirâmide da IA. E você? 👉 [link]"*
- Loop clássico de teste de personalidade: o resultado é identidade → a pessoa compartilha → o quiz traz a próxima.

### Motor 2 — Prova da Pirâmide (final)
- Badge de conclusão compartilhável (§9). Quem termina divulga; quem vê o badge quer o seu.

### Motor 3 — Série de 6 reels (1 por camada)
Roteiro pronto a partir das frases-âncora — produção via skills `video-explicativo`/`videoprodutor`:
1. 🟢 "Prompt é a pergunta." — o e-mail difícil em 4 versões (30s)
2. 🔵 "Intenção é o destino." — o post perfeito que vendeu zero
3. 🟣 "Contexto é o mapa." — a IA não é fraca, está cega
4. 🟡 "Aproveitamento é o método." — o acerto que sua empresa esqueceu
5. 🟦 "Arquitetura é o sistema." — 10 prompts bons não fazem um processo
6. 🌹 "Evolução é o aprendizado acumulado." — por que o vídeo que bombou não te ensinou nada
- Cada reel termina com: "Descubra sua camada → link na bio" (aponta pro diagnóstico).

### Motor 4 — Conteúdo de ancoragem
- **Carrossel-pirâmide** (7 slides: capa + 6 camadas) — formato que mais performa no Instagram/LinkedIn.
- **Post contrarian de lançamento:** "Você está atrasado na IA? Ótimo. — Quem entra no topo vê complexidade. Quem começa na base entende evolução."
- **Post-polêmica:** "Pare de salvar prompts. 100 prompts salvos ≠ saber usar IA."

### Sequência de lançamento
1. Semana -1: post contrarian + carrossel-pirâmide (semear o framework)
2. Lançamento: diagnóstico no ar + reel 1
3. Semanas 1–6: 1 reel/camada/semana, cada um apontando pro diagnóstico
4. Contínuo: badges da prova gerando prova social orgânica

---

## 12. Landing page (index.html)

1. **Hero:** título-promessa ("Você não precisa de 100 prompts. Precisa de 6 camadas.") + frase "Quem entra no topo vê complexidade. Quem começa na base entende evolução." + CTA **"Descobrir minha camada (60s)"**.
2. **Pirâmide interativa (hero SVG):** 6 camadas clicáveis → trilhas. Cor por camada.
3. **Diagnóstico de nível** (6 perguntas + card compartilhável).
4. **"Você está atrasado? Ótimo."** — a tese do retardatário.
5. **Grid das 6 trilhas** (cor + frase-âncora + caso-âncora em 1 linha + nº módulos).
6. **"Na sua profissão"** — 5 perfis, 1 linha cada.
7. **O kit que você leva** (os 6 artefatos + mapa-portfólio).
8. **Prova da Pirâmide** (teaser do badge).
9. **CTA final + INEMA.CLUB** (`text-sky-400`).

---

## 13. Roadmap de produção

1. **Landing** com pirâmide + diagnóstico (motor viral primeiro — começa a captar antes do curso completo).
2. **Trilha 1** completa (Base Zero + verificação) — destrava o retardatário.
3. Trilhas **2 e 3** (Intenção, Contexto + privacidade).
4. Trilha **4** (Aproveitamento).
5. Trilhas **5 e 6** (Arquitetura, Evolução + capstone portfólio).
6. **Prova da Pirâmide** + badges.
7. Revisão com `revisar-curso` + registro no **portal inema.club**.
8. Produção dos 6 reels (skills de vídeo) conforme sequência de lançamento.

Padrões INEMA em todas as páginas: nav completo, theme toggle, SVG futurista por módulo, mapa da trilha, ≥6 tópicos/módulo, INEMA.CLUB.

> **Nota comercial:** se o curso for comercial, imagens raster via `qwen-edit-2511` (FLUX klein/dev é non-commercial). SVGs inline sem restrição.

---

## 14. Registro das decisões (v2)

- ✅ Verificação/alucinação → **T1** (Base Zero, tópico 6). Privacidade/dados → **T3** (módulo 3.1, tópico 7).
- ✅ Caso-âncora exclusivo por trilha (anti-repetição T1–T3).
- ✅ T5 travada em no-code (proteger o público retardatário).
- ✅ Box "Na sua profissão" (5 perfis) em todas as trilhas.
- ✅ Capstone T6 = peça de portfólio + post LinkedIn + script de entrevista.
- ✅ Título-promessa + 2 motores virais (diagnóstico + prova com badge) + 6 reels + sequência de lançamento.
- ✅ Prova final: 12 questões-caso, correção instantânea com gabarito comentado (ver a resposta = aprender), client-side, badge compartilhável.
