# EPIC-001 — Império Start Blog
**Status:** In Progress
**Owner:** Adriano Martins
**Criado:** 05/06/2026
**Agente:** Orion (aiox-master)

---

## Visão

Construir um ecossistema de 10+ blogs monetizados com Google AdSense, operado por squads de IA com supervisão humana de 3 pessoas. Receita exclusivamente via AdSense, sem venda de produtos.

**Metodologia base:** Academia Start Blog — Cris Franklin
**Abordagem:** Blog genérico validado primeiro → escala depois

---

## Critérios de Sucesso

- [ ] Primeiro blog aprovado no Google AdSense
- [ ] Primeiros $10/dia de receita validados
- [ ] Pipeline de conteúdo IA + revisão humana funcionando
- [ ] 10+ blogs ativos e otimizados
- [ ] Receita escalável em múltiplos idiomas

---

## Arquitetura de IA

### NEXUS — Mente Mestre
Orquestrador central. Interface entre equipe humana e todos os squads.

### 7 Squads Operacionais

| # | Squad | Missão |
|---|-------|--------|
| 1 | 🔭 RADAR | Inteligência de mercado, nichos e keywords |
| 2 | 🏗️ FÁBRICA | Criação de novos blogs do zero |
| 3 | ✍️ CONTEÚDO | Produção de artigos em escala |
| 4 | 📢 TRÁFEGO | Google Ads — campanhas e lances |
| 5 | 💰 RECEITA | Otimização AdSense e monetização |
| 6 | 🌍 ESCALA | Expansão internacional (EN, ES) |
| 7 | 🛡️ OPERAÇÕES | Monitoramento 24/7 e alertas |

### Squad ALMA — Anti-Detecção IA (CRÍTICO)
Pipeline de humanização: DNA Extractor → Voice Injector → EEAT Builder → Humanizer → Detector Tester → Human Gate

---

## Stories

### Story 001 — Base de Conhecimento do Método
**Status:** ✅ Done
**Descrição:** Transcrever 153 aulas da Academia Start Blog e montar o Documento Mestre do Método.

**Tasks:**
- [x] Identificar plataforma (Cademi + Panda Video)
- [x] Configurar pipeline de extração (yt-dlp + OpenAI Whisper)
- [x] Script de download e transcrição rodando
- [x] 151/153 aulas transcritas (98.7% — 1 arquivo muito grande para API, 1 sem vídeo)
- [x] Montar Documento Mestre do Método (585 linhas, ~6.200 palavras, 3 fases completas)
- [ ] Alimentar agentes com o conhecimento do curso (próxima etapa: Story 003/004)

---

### Story 002 — Três Blogs: Planejamento e Conteúdo da Fase de Fundação
**Status:** ✅ Done
**Descrição:** Definição e criação de conteúdo para os 3 primeiros blogs do Império Start Blog.

**Tasks:**
- [x] Blog 01 (Tecnologia & Apps) — nicho, categorias, 30 artigos criados
- [x] Blog 02 (Educação & Cursos) — nicho, categorias, 30 artigos criados
- [x] Blog 03 (Pets & Animais) — nicho, categorias, 30 artigos criados
- [x] 90 artigos totais prontos para publicar no WordPress
- [x] Story documentada em `docs/stories/002-tres-blogs-fundacao.story.md`
- [ ] Validar nichos no Google (ação do Adriano — < 200k resultados)
- [ ] Escolher domínios para os 3 blogs
- [ ] Publicar artigos + configurar WordPress (Story 003)

---

### Story 003 — Squad ALMA v1
**Status:** 📋 Backlog
**Descrição:** Construir o squad de humanização de conteúdo básico.

**Tasks:**
- [ ] Elicitação de DNA de escrita da equipe
- [ ] Agente Voice Injector básico
- [ ] Agente EEAT Builder básico
- [ ] Agente Humanizer básico
- [ ] Integração com detectores GPTZero + Originality.ai
- [ ] Checkpoint de revisão humana (Human Gate)

---

### Story 004 — Squad Conteúdo v1
**Status:** 📋 Backlog
**Descrição:** Primeiro pipeline funcional de criação de artigos.

**Tasks:**
- [ ] Agente Keyword Strategist
- [ ] Agente Writer (alimentado com método Cris Franklin)
- [ ] Agente SEO Editor
- [ ] Integração com WordPress API (publicação automática)
- [ ] Fluxo completo: keyword → rascunho → ALMA → revisão → publicação

---

### Story 005 — Aprovação AdSense
**Status:** 📋 Backlog
**Descrição:** Submeter e aprovar o primeiro blog no Google AdSense.

**Tasks:**
- [ ] 15-20 artigos publicados e indexados
- [ ] Páginas obrigatórias no ar
- [ ] Blog com 30+ dias de idade
- [ ] Submissão para aprovação
- [ ] Configuração dos ad units

---

### Story 006 — Squad Tráfego v1
**Status:** 📋 Backlog (após aprovação AdSense)
**Descrição:** Primeira campanha Google Ads funcionando.

**Tasks:**
- [ ] Conta Google Ads configurada
- [ ] Primeira campanha criada
- [ ] Agente Bid Manager básico
- [ ] Agente Performance Analyst
- [ ] ROI positivo validado

---

## Infraestrutura Disponível

| Item | Status |
|------|--------|
| Domínios | ✅ Vários disponíveis |
| WordPress | ✅ Instalações existentes |
| OpenAI API | ✅ Ativa |
| Google Ads | ❓ A confirmar |
| Google Analytics | ❓ A confirmar |
| Search Console | ❓ A confirmar |

---

## DNA de Escrita
**Status:** ⏳ Pendente
**Quando fazer:** Após definir o primeiro blog
**O que precisa:** 500+ palavras escritas pela equipe (e-mails, textos, mensagens)
**Responsável:** Orion faz a elicitação quando solicitado

---

## Arquivos do Projeto

| Arquivo | Descrição |
|---------|-----------|
| `imperio-startblog/ARQUITETURA-GERAL.md` | Arquitetura completa detalhada |
| `transcrever_curso.py` | Script de extração e transcrição |
| `transcricoes/` | Aulas transcritas do curso |

---

## Princípio Fundamental

> **IA executa. Humano aprova. Google ama.**
