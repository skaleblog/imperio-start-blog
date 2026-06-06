# Story 002 — Três Blogs: Planejamento e Conteúdo da Fase de Fundação

**Epic:** EPIC-001 — Império Start Blog
**Status:** ✅ Done
**Criado:** 05/06/2026
**Agente:** Orion (aiox-master)

---

## Descrição

Definição, estruturação e criação de conteúdo para os 3 primeiros blogs do Império Start Blog, seguindo a metodologia Academia Start Blog (Cris Franklin) — Fase de Fundação. Cada blog tem nicho de aprovação (técnica das 4 camadas), 3 categorias e 30 artigos de base completos prontos para publicar no WordPress.

---

## Critérios de Aceite

- [x] 3 blogs definidos com nicho de aprovação (técnica das 4 camadas)
- [x] Cada nicho validado como não-YMYL
- [x] Cada blog com 3 categorias (máx. 2 palavras, menu em 1 linha)
- [x] 30 artigos por blog = 90 artigos no total
- [x] Artigos com estrutura correta (intro + 4 subtítulos + conclusão)
- [x] Mínimo 600 palavras por artigo
- [x] Conteúdo original em PT-BR, sem links externos
- [x] Metadados de categoria e palavras-chave em cada artigo
- [x] Arquivos salvos em estrutura de pastas organizada
- [x] Story documentada e epic atualizado

---

## Os 3 Blogs

### Blog 01 — Tecnologia & Apps
**Prioridade:** #1 (maior CPC e potencial de escala)
**Nicho de aprovação:** Aplicativos de organização de tarefas no iPhone para estudantes universitários
**Pivot pós-aprovação:** Tutoriais amplos de tecnologia (recuperar contas, erros de apps, configurações)
**Expansão:** Inglês (EUA/UK) — CPC 3-5x maior

| Categoria | Artigos |
|-----------|---------|
| Aplicativos | 10 artigos (01-10) |
| Configurações | 10 artigos (11-20) |
| Produtividade | 10 artigos (21-30) |

**Arquivos:**
- Planejamento: `imperio-startblog/blogs/blog-01-tecnologia-apps.md`
- Artigos: `imperio-startblog/blogs/blog-01-tecnologia-apps/artigos/` (30 arquivos .md)

---

### Blog 02 — Educação & Cursos Online
**Prioridade:** #2 (CPC alto, mercado enorme no Brasil)
**Nicho de aprovação:** Como aprender inglês assistindo séries na Netflix para adultos acima de 40 anos
**Pivot pós-aprovação:** Cursos gratuitos, certificados, plataformas educacionais, concursos
**Expansão:** Espanhol (Colômbia, Chile, Argentina, México)

| Categoria | Artigos |
|-----------|---------|
| Inglês | 10 artigos (01-10) |
| Plataformas | 10 artigos (11-20) |
| Carreira | 10 artigos (21-30) |

**Arquivos:**
- Planejamento: `imperio-startblog/blogs/blog-02-educacao-cursos.md`
- Artigos: `imperio-startblog/blogs/blog-02-educacao-cursos/artigos/` (30 arquivos .md)

---

### Blog 03 — Pets & Animais de Estimação
**Prioridade:** #3 (aprovação mais fácil, CPC médio)
**Nicho de aprovação:** Como cuidar de hamster anão russo em apartamento pequeno
**Pivot pós-aprovação:** Cuidados com pets em geral (cachorros, gatos, ração, saúde animal)
**Expansão:** Espanhol (Argentina — maior mercado de pets da AL)

| Categoria | Artigos |
|-----------|---------|
| Hamsters | 10 artigos (01-10) |
| Alimentação | 10 artigos (11-20) |
| Saúde | 10 artigos (21-30) |

**Arquivos:**
- Planejamento: `imperio-startblog/blogs/blog-03-pets-animais.md`
- Artigos: `imperio-startblog/blogs/blog-03-pets-animais/artigos/` (30 arquivos .md)

---

## Estrutura de Arquivos Completa

```
imperio-startblog/
├── ARQUITETURA-GERAL.md              ← Arquitetura dos 7 squads + ALMA
├── DOCUMENTO-MESTRE-METODO.md        ← Método completo da Cris Franklin
├── blogs/
│   ├── INDICE-BLOGS.md               ← Índice e estratégia dos 3 blogs
│   ├── blog-01-tecnologia-apps.md    ← Planejamento Blog 01
│   ├── blog-02-educacao-cursos.md    ← Planejamento Blog 02
│   ├── blog-03-pets-animais.md       ← Planejamento Blog 03
│   ├── blog-01-tecnologia-apps/
│   │   └── artigos/ (30 arquivos)
│   ├── blog-02-educacao-cursos/
│   │   └── artigos/ (30 arquivos)
│   └── blog-03-pets-animais/
│       └── artigos/ (30 arquivos)

docs/stories/
├── EPIC-001-imperio-startblog.md
└── 002-tres-blogs-fundacao.story.md  ← ESTE ARQUIVO

transcricoes/
└── textos/ (151 aulas transcritas)
```

---

## O que falta para colocar os blogs no ar

### Pendente — Ação do Adriano
- [ ] Validar os 3 nichos no Google (pesquisar e confirmar < 200k resultados)
- [ ] Escolher/confirmar domínios para os 3 blogs
- [ ] Contratar hospedagem (se necessário)

### Pendente — Próxima Story (003)
- [ ] Gerar textos das 6 páginas obrigatórias para cada blog (18 páginas)
- [ ] Configurar WordPress (tema Astra/Neve, plugins obrigatórios)
- [ ] Publicar os 30 artigos em cada WordPress
- [ ] Configurar sitemap + robots.txt + Search Console
- [ ] Executar checklist do método antes de enviar
- [ ] Enviar os 3 blogs para aprovação no AdSense

---

## Notas

- O método da Cris exige **reestruturação** do blog após a aprovação — os artigos atuais são para aprovação, não para monetização final
- Blog 03 (Pets) tende a ser aprovado mais rápido — nicho mais específico
- Blog 01 (Tecnologia) tem maior potencial de receita no longo prazo
- Squad ALMA ainda não foi ativado — artigos passaram por revisão básica mas não pelo pipeline completo de humanização (a ativar na Story 003 do Squad ALMA)

---

## Change Log

| Data | Agente | Ação |
|------|--------|------|
| 05/06/2026 | Orion (aiox-master) | Story criada, 90 artigos gerados, epic atualizado |

