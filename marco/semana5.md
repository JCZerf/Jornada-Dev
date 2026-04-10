# Semana 5 \u2014 21 de mar\u00e7o de 2026

## SITUA\u00c7\u00c3O
In\u00edcio de projeto pessoal Financial Insight para an\u00e1lise de Fundos Imobili\u00e1rios (FII). Necessidade de coletar dados de FIIs automaticamente, normalizar informa\u00e7\u00f5es financeiras e armazenar em banco de dados para an\u00e1lises futuras. Projeto exigia scraping robusto e modelo de dados bem estruturado.

## TAREFA
- Criar pipeline de scraping de dados de FIIs
- Desenvolver normaliza\u00e7\u00e3o de dados financeiros
- Modelar banco de dados Django para FIIs
- Implementar extra\u00e7\u00e3o com Playwright
- Criar sistema de ingest\u00e3o paralela
- Dockerizar aplica\u00e7\u00e3o com Playwright
- Documentar setup e uso

## A\u00c7\u00c3O

### Modelagem de Dados
- Criei models Django para RealEstateFund e RealEstateFundDetail
- Implementei campos para dados financeiros, operacionais e identifica\u00e7\u00e3o
- Refatorei nomes de campos de PT para EN (ticker, segment, property_count, etc.)
- Adicionei indexes e constraints para performance e integridade
- Utilizei PositiveIntegerField para quantidades

### Pipeline de Scraping
- Desenvolvi bot Playwright para extra\u00e7\u00e3o de dados de FIIs
- Implementei normaliza\u00e7\u00e3o de valores monet\u00e1rios e percentuais
- Criei ingest\u00e3o paralela de detalhes com controle de abas (BOT_MAX_DETAIL_TABS)
- Implementei upsert l\u00f3gico por ticker
- Adicionei profiling de recursos (timing, opera\u00e7\u00f5es DB)

### Deploy e Configura\u00e7\u00e3o
- Criei Dockerfile.ingestor com Playwright Python
- Configurei PostgreSQL para persist\u00eancia
- Implementei migrations Django
- Documentei vari\u00e1veis de ambiente
- Criei scripts de profiling de recursos

## RESULTADO
- Pipeline completo de scraping FIIs funcional
- Dados normalizados e estruturados em PostgreSQL
- Processamento paralelo otimizado
- Containeriza\u00e7\u00e3o com Docker
- Modelo de dados limpo e extensvel
- M\u00e9tricas de performance e profiling
- Base para an\u00e1lises financeiras futuras
- Documenta\u00e7\u00e3o completa de setup

---

### Stack T\u00e9cnico
- **Django + PostgreSQL** - ORM e persist\u00eancia
- **Playwright** - Scraping de dados web
- **Python Async** - Processamento paralelo
- **Docker** - Containeriza\u00e7\u00e3o com Playwright
- **Data Normalization** - Limpeza de valores financeiros
- **Database Migrations** - Versionamento de schema

### Aprendizados
- Normaliza\u00e7\u00e3o de dados financeiros \u00e9 crucial para an\u00e1lises
- Nomes em ingl\u00eas melhoram legibilidade de c\u00f3digo
- Processamento paralelo acelera ingest\u00e3o significativamente
- Playwright ideal para sites din\u00e2micos/JavaScript-heavy
- Upsert por ticker evita duplica\u00e7\u00e3o
- Profiling ajuda identificar bottlenecks
- Migrations Django facilitam evolu\u00e7\u00e3o de schema

### Desafios T\u00e9cnicos
- Extra\u00e7\u00e3o de dados de m\u00faltiplas p\u00e1ginas din\u00e2micas
- Normaliza\u00e7\u00e3o de formatos monet\u00e1rios diversos
- Controle de paralelismo sem exaurir recursos
- Configura\u00e7\u00e3o Playwright em Docker
- Defini\u00e7\u00e3o de modelo de dados flex\u00edvel
- Tratamento de dados ausentes ou inconsistentes

### PRs Relacionados
- [PR#1 financial_insight](https://github.com/JCZerf/financial_insight/pull/1) - Pipeline scraping inicial
- [PR#2 financial_insight](https://github.com/JCZerf/financial_insight/pull/2) - Refactor async + observability
