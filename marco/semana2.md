# Semana 2 \u2014 12 a 16 de mar\u00e7o de 2026

## SITUA\u00c7\u00c3O
In\u00edcio do desenvolvimento de sistema RPA (Robotic Process Automation) para automa\u00e7\u00e3o de consultas ao Portal da Transpar\u00eancia. Projeto desafio Most/Hyperautomation exigindo bot com Playwright, modulariza\u00e7\u00e3o e implementa\u00e7\u00e3o dos 4 primeiros passos: navega\u00e7\u00e3o, busca, extra\u00e7\u00e3o e evidências.

## TAREFA
- Implementar bot RPA com Playwright para web scraping
- Criar navega\u00e7\u00e3o automatizada no Portal da Transpar\u00eancia
- Desenvolver extra\u00e7\u00e3o de dados estruturados
- Implementar captura de evid\u00eancias (screenshots)
- Modularizar c\u00f3digo para manuten\u00e7\u00e3o
- Validar busca por CPF, NIS e nome

## A\u00c7\u00c3O

### Implementa\u00e7\u00e3o RPA Base
- Desenvolvi bot com Playwright e Python
- Implementei navega\u00e7\u00e3o automatizada com tratamento de esperas
- Criei extra\u00e7\u00e3o de dados estruturados do portal
- Implementei captura de screenshots como evid\u00eancia

### Modulariza\u00e7\u00e3o
- Separei c\u00f3digo em m\u00f3dulos: browser, navigation, extraction, scraper
- Criei estrutura clara de responsabilidades
- Organizei projeto para facilitar manuten\u00e7\u00e3o futura
- Documentei fluxo e uso do bot

### Valida\u00e7\u00f5es
- Implementei classifica\u00e7\u00e3o de tipo de consulta (CPF/NIS/nome)
- Criei valida\u00e7\u00e3o e mascaramento de dados sens\u00edveis
- Adicionei tratamento robusto de erros

## RESULTADO
- Bot RPA funcional para Portal da Transpar\u00eancia
- 4 primeiros passos do desafio implementados
- C\u00f3digo modular e manten\u00edvel
- Extra\u00e7\u00e3o estruturada de benef\u00edcios
- Evid\u00eancias capturadas automaticamente
- Valida\u00e7\u00f5es de entrada robustas
- Base s\u00f3lida para API REST

---

### Stack T\u00e9cnico
- **Python** - Linguagem principal do bot
- **Playwright** - Automa\u00e7\u00e3o browser headless
- **Web Scraping** - Extra\u00e7\u00e3o de dados estruturados
- **Async/Await** - Programa\u00e7\u00e3o ass\u00edncrona
- **Modular Architecture** - Separa\u00e7\u00e3o de responsabilidades

### Aprendizados
- Playwright oferece controle robusto de navegadores
- Modulariza\u00e7\u00e3o \u00e9 crucial em projetos RPA
- Web scraping requer tratamento cuidadoso de esperas
- Evid\u00eancias s\u00e3o essenciais para auditoria
- Valida\u00e7\u00f5es previnem erros de entrada
- Async/await melhora performance de I/O

### Desafios T\u00e9cnicos
- Esperas din\u00e2micas em carregamentos de p\u00e1gina
- Extra\u00e7\u00e3o confi\u00e1vel de dados din\u00e2micos
- Tratamento de m\u00faltiplos tipos de consulta
- Organiza\u00e7\u00e3o modular sem acoplamento
- Captura de screenshots em momento correto

### PRs Relacionados
- [PR#1 most-rpa](https://github.com/JCZerf/most-rpa-hyperautomation/pull/1) - Bot inicial 4 passos
- [PR#2 most-rpa](https://github.com/JCZerf/most-rpa-hyperautomation/pull/2) - Modulariza\u00e7\u00e3o
