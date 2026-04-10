# Semana 4 \u2014 18 a 22 de novembro de 2025

## SITUA\u00c7\u00c3O
A rede social Someone Talking precisava de funcionalidades essenciais para engajamento: sistema de likes e fotos de perfil de usu\u00e1rios. Era necess\u00e1rio permitir upload de imagens no cadastro, atualiza\u00e7\u00e3o de fotos de perfil e implementar sistema completo de curtidas nos posts do feed.

## TAREFA
- Implementar upload de fotos de perfil no cadastro e atualiza\u00e7\u00e3o
- Criar sistema de likes no backend com persist\u00eancia
- Desenvolver UI de likes no frontend Flutter
- Implementar ordena\u00e7\u00e3o por likes e data
- Suportar multipart/form-data para envio de imagens
- Armazenar arquivos e URLs no sistema

## A\u00c7\u00c3O

### Sistema de Fotos de Perfil
- Implementei endpoint multipart/form-data no NestJS para receber fotos
- Configurei armazenamento de arquivos na pasta uploads/
- Criei campo profilePhotoUrl no modelo de usu\u00e1rio
- Desenvolvi sele\u00e7\u00e3o de imagem no Flutter com preview
- Implementei \u00edcone de c\u00e2mera na tela de cadastro
- Adicionei endpoint de atualiza\u00e7\u00e3o de foto ap\u00f3s cadastro

### Sistema de Likes
- Criei modelo e endpoints REST para likes no backend
- Implementei contador de likes por post
- Desenvolvi UI de bot\u00e3o de like no Flutter
- Adicionei ordena\u00e7\u00e3o: mais novos e mais curtidos
- Sincronizei estado de likes em tempo real no frontend
- Documentei API de likes para uso consistente

## RESULTADO
- Upload de fotos funcionando no cadastro e atualiza\u00e7\u00e3o
- Preview de imagem antes do envio
- Sistema de likes completo e responsivo
- Ordena\u00e7\u00e3o de feed por popularidade e data
- Armazenamento seguro de imagens em servidor
- Engajamento de usu\u00e1rios significativamente melhorado

---

### Stack T\u00e9cnico
- **NestJS** - Multipart/form-data, file upload, likes API
- **Flutter** - Image picker, preview, UI de likes
- **File System** - Armazenamento de uploads/
- **REST API** - Endpoints de likes e fotos
- **State Management** - Sincroniza\u00e7\u00e3o de likes

### Aprendizados
- Upload de arquivos multipart requer configura\u00e7\u00e3o espec\u00edfica
- Preview de imagem melhora UX antes do envio
- Sistema de likes aumenta engajamento de usu\u00e1rios
- Ordena\u00e7\u00e3o din\u00e2mica \u00e9 essencial em feeds sociais
- Armazenamento de URLs facilita acesso a imagens

### Desafios T\u00e9cnicos
- Configura\u00e7\u00e3o de multipart/form-data no NestJS
- Gerenciamento de arquivos no servidor
- Sincroniza\u00e7\u00e3o de estado de likes em tempo real
- Preview de imagem antes do upload
- Valida\u00e7\u00e3o de tipos de arquivo permitidos

### PRs Relacionados
- [PR#2 api_someone_talking](https://github.com/JCZerf/api_someone_talking/pull/2) - Fotos de perfil
- [PR#3 api_someone_talking](https://github.com/JCZerf/api_someone_talking/pull/3) - Sistema de likes
- [PR#2 app_someone_talking](https://github.com/JCZerf/app_someone_talking/pull/2) - Upload fotos frontend
- [PR#3 app_someone_talking](https://github.com/JCZerf/app_someone_talking/pull/3) - Likes e ordena\u00e7\u00e3o
