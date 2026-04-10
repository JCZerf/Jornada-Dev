# Semana 2 — 10 a 14 de junho de 2025

## SITUAÇÃO
O aplicativo Brapp possuía um ranking único de usuários sem possibilidade de filtragem, limitando a experiência do usuário que queria ver classificações específicas por categoria (Iron, Gold, Silver, etc.). Era necessário implementar uma solução que permitisse visualização segmentada.

## TAREFA
- Implementar sistema de categorias no ranking de usuários
- Criar filtros dinâmicos para visualização por categoria
- Desenvolver lógica de filtragem sem comprometer performance
- Planejar compartilhamento de rankings filtrados (preparação)

## AÇÃO
- Análise da estrutura atual do ranking no Firestore
- Prototipagem de interface com dropdown para seleção de categorias
- Implementação de lógica para filtragem dinâmica usando `setState()`
- Testes de performance com listas filtradas em tempo real
- Estruturação de dados no Firebase para suportar múltiplos contextos
- Validação da responsividade durante atualizações da lista

## RESULTADO
- Filtro por categorias funcionando corretamente
- Interface responsiva durante filtragem em tempo real
- Base técnica preparada para compartilhamento (próxima semana)
- Performance mantida mesmo com dados grandes
- Primeira funcionalidade implementada end-to-end

---

### Stack Técnico
- **Flutter** - Dropdown, setState(), ListView.builder
- **Firestore** - Queries filtradas, estruturação de dados
- **Dart** - Lógica condicional, manipulação de listas
- **UI/UX** - Design responsivo, feedback visual

### Aprendizados
- Manipulação de estado em Flutter com filtros dinâmicos
- Otimização de queries no Firestore para performance
- Importância do planejamento antes da implementação

### Desafios Técnicos
- Manter responsividade durante filtragem de listas grandes
- Estruturar dados para suportar múltiplos contextos de visualização
- Equilibrar funcionalidade e performance
