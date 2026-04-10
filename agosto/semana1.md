# Semana 1 - 28 de julho a 01 de agosto de 2025

## SITUACAO
Continuação dos ajustes de tolerância de GPS e preparação para features mais avançadas. Necessidade de estabilizar configurações de tolerância e lançar versões corretivas. Também foi identificada a necessidade de ignorar trilhas vazias para evitar problemas de renderização.

## TAREFA
- Ajustar tolerância entre pontos de atividade e trilha para 50 metros
- Configurar raio de 20m para pontos de início e fim
- Ignorar trilhas vazias na renderização do mapa
- Lançar versões corretivas (2.1.4 a 2.1.7)
- Estabilizar cálculo de porcentagem de volta

## ACAO

### Ajustes de Tolerância
- Configurei tolerância de 50m para cálculo de volta e porcentagem
- Defini raio de 20m para detecção de pontos de início e fim
- Testei diferentes configurações em cenários reais
- Balanceei precisão com usabilidade em dispositivos variados

### Correções de Estabilidade
- Implementei ignorar trilhas vazias no mapa de atividades
- Corrigi cálculo de porcentagem com novas tolerâncias
- Ajustei detecção de volta completa vs incompleta

### Releases
- Versão 2.1.4 - Nova tolerância 50M
- Versão 2.1.5 - Alteração tolerância para 20M
- Versão 2.1.6 e 2.1.7 - Ajustes finos de tolerância

## RESULTADO
- Sistema de tolerâncias estabilizado
- Zero crashes por trilhas vazias
- Cálculo de volta mais preciso
- 4 versões corretivas lançadas (2.1.4 a 2.1.7)
- Base sólida para features avançadas
- Experiência consistente em diferentes dispositivos

---

### Stack Técnico
- **Flutter** - Interface e renderização de mapas
- **GPS** - Cálculos de tolerância e distância
- **Firebase** - Sincronização de dados de trilhas
- **Algoritmos** - Cálculo de porcentagem e detecção de volta

### Aprendizados
- Tolerâncias de GPS precisam de ajuste fino iterativo
- Diferentes cenários exigem diferentes configurações
- Versões incrementais permitem rollback rápido
- Ignorar dados inválidos é melhor que crash

### Desafios Técnicos
- Encontrar tolerância ideal para todos os cenários
- Balancear precisão com performance
- Manter compatibilidade entre versões
- Testar em dispositivos com GPS de diferentes qualidades

### Commits Relacionados
- change tolerance 20 to 50 for start-trail and end-trail
- Ignore empty trails in activity map rendering
- new tolerance 50M
- alteração tolerância para 20M
- Change the tolerance used for lap calculation and percentage to 50
