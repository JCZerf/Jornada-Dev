# Agosto 2025 - Brapp (valoraresoftware)

> Mês de features avançadas - Tolerâncias personalizadas, GPS e foto de perfil

## SITUAÇÃO

Com a base sólida de performance e validações, o foco passou para funcionalidades mais avançadas: sistema de tolerâncias personalizadas por trilha, aumento da precisão do GPS e implementação de upload de foto de perfil.

## PRINCIPAIS ENTREGAS

### Sistema de Tolerâncias Personalizadas
- Implementação de tolerâncias configuráveis por trilha
- Ajuste fino de tolerância entre pontos de atividade e trilha (50 metros)
- Raio configurável para pontos de início e fim (20 metros)
- Cálculo de porcentagem de volta com tolerância ajustada

### Precisão de GPS
- Aumento das configurações de precisão do GPS
- Melhoria na detecção de posição do usuário
- Configurações otimizadas para diferentes dispositivos

### Upload de Foto de Perfil
- Implementação completa de upload de foto
- Integração com Firebase Storage
- Compressão e otimização de imagens
- Novas dependências para manipulação de imagem

## COMMITS RELEVANTES

```
2025-08-01 | fix: Adjusts the tolerance between activity points and trail to 50m
2025-08-01 | Update app version to 2.1.6
2025-08-01 | Update app version to 2.1.7
2025-08-04 | Change tolerance for lap calculation (50) and start/end radius (20)
2025-08-04 | Update app version to 2.1.8
2025-08-07 | feat: Implementa sistema de tolerâncias personalizadas para trilhas
2025-08-07 | feat: increase GPS precision settings
2025-08-08 | feat: implementa upload de foto de perfil
2025-08-08 | novas dependencias
2025-08-11 | Merge PR #62 - custom-tolerance-settings
2025-08-11 | Merge PR #63 - increase-gps-precision
2025-08-11 | Merge PR #64 - profile-image-upload
2025-08-11 | Update app version to 2.2.0
```

## RESULTADO

- App evoluiu de v2.1.5 para v2.2.0 (versão major)
- Sistema de tolerâncias flexível para diferentes trilhas
- GPS mais preciso para melhor experiência
- Personalização de perfil com foto
- 4 PRs mergeados neste mês

---

### Stack Técnico
- **Flutter** - Image picker, upload handlers
- **Firebase Storage** - Upload e gerenciamento de arquivos
- **GPS/Geolocation** - Configurações de precisão
- **Dart** - Lógica de tolerâncias dinâmicas

### Aprendizados
- Implementação de upload de arquivos com Firebase
- Configuração de precisão de GPS em dispositivos móveis
- Sistema de tolerâncias configuráveis para diferentes contextos
- Gerenciamento de dependências para novas funcionalidades
