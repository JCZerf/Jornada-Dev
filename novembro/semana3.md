# Semana 3 \u2014 17 a 21 de novembro de 2025

## SITUA\u00c7\u00c3O
Desenvolvimento de rede social Someone Talking. O projeto precisava de funcionalidades b\u00e1sicas de feed com opera\u00e7\u00f5es CRUD completas tanto no backend (NestJS) quanto no frontend (Flutter). Necess\u00e1rio estabelecer arquitetura base para futuras funcionalidades sociais.

## TAREFA
- Implementar CRUD completo do feed no backend NestJS
- Desenvolver interface do feed no Flutter com padr\u00e3o MVVM
- Criar sistema de publica\u00e7\u00f5es com persist\u00eancia
- Ajustar \u00edcone da aplica\u00e7\u00e3o
- Estabelecer comunica\u00e7\u00e3o API-App funcional

## A\u00c7\u00c3O

### Backend - API NestJS
- Implementei endpoints REST para CRUD de posts do feed
- Estruturei models e controllers seguindo padr\u00f5es NestJS
- Configurei valida\u00e7\u00f5es de dados e tratamento de erros
- Documentei API para facilitar integra\u00e7\u00e3o frontend

### Frontend - Flutter
- Desenvolvi telas de feed com lista de posts
- Implementei padr\u00e3o MVVM (Model-View-ViewModel) para separa\u00e7\u00e3o de responsabilidades
- Criei formul\u00e1rios para criar e editar posts
- Ajustei \u00edcone da aplica\u00e7\u00e3o para identidade visual
- Integrei comunica\u00e7\u00e3o HTTP com backend

## RESULTADO
- CRUD de feed funcional end-to-end (backend + frontend)
- Arquitetura MVVM estabelecida para escala do projeto
- Interface responsiva e intuitiva para publica\u00e7\u00f5es
- Comunica\u00e7\u00e3o API-App validada e est\u00e1vel
- Base s\u00f3lida para funcionalidades sociais futuras

---

### Stack T\u00e9cnico
- **NestJS** - Framework backend Node.js, REST API, TypeScript
- **Flutter** - Framework mobile multiplataforma
- **Dart** - Linguagem para Flutter, async/await
- **MVVM Pattern** - Arquitetura frontend
- **HTTP** - Integra\u00e7\u00e3o API-App

### Aprendizados
- Padr\u00e3o MVVM melhora manuten\u00e7\u00e3o e testabilidade
- NestJS oferece estrutura robusta para APIs escal\u00e1veis
- Separa\u00e7\u00e3o clara de responsabilidades facilita evolu\u00e7\u00e3o
- Documenta\u00e7\u00e3o de API economiza tempo de integra\u00e7\u00e3o

### Desafios T\u00e9cnicos
- Sincroniza\u00e7\u00e3o de estado entre frontend e backend
- Implementa\u00e7\u00e3o correta de padr\u00e3o MVVM em Flutter
- Tratamento adequado de erros HTTP
- Organiza\u00e7\u00e3o de c\u00f3digo para manuten\u00e7\u00e3o futura

### PRs Relacionados
- [PR#1 api_someone_talking](https://github.com/JCZerf/api_someone_talking/pull/1) - CRUD b\u00e1sico do feed
- [PR#1 app_someone_talking](https://github.com/JCZerf/app_someone_talking/pull/1) - Feed no front-end
