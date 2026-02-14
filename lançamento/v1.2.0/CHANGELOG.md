# 📋 Changelog

## v1.2.0 - 14 de fevereiro de 2026


---

## 🎯 O QUE FOI ADICIONADO/ALTERADO

### ✨ Novas Funcionalidades
- Botão "Não Gostei" com armazenamento persistente (Hive)
- Importação de playlists Spotify e YouTube Music
- Fila inteligente aprimorada com filtro automático de dislikes
- Toggle entre modo inteligente e aleatório durante reprodução
- Controle "Conteúdo Personalizado" nas configurações
- Ícones redesenhados em roxo Muvy com suporte adaptável

### 🎨 Melhorias Visuais
- Ícones do app novo estilo roxo Muvy
- Suporte a ícones adaptáveis (Android 13+)
- Ícones em múltiplas densidades (mdpi, hdpi, xhdpi, xxhdpi, xxxhdpi)
- Artista centralizado corretamente no player
- Títulos longos com scroll suave e contínuo
- Interface melhor em telas pequenas

### 🐛 Correções
- Corrigidos erros de Map casting na fila inteligente
- Eliminados race conditions no carregamento de filas
- Melhorado desempenho de busca em bibliotecas grandes (10k+ músicas)
- Histórico de buscas ordenado corretamente
- AppBar com melhor suporte a overflow em telas pequenas
- Reduzido travamento ao carregar filas grandes
- Melhorado desempenho em dispositivos baixa-end

### 📱 Suporte a Plataformas
- ✅ Windows (7, 8, 10, 11)
- ✅ Android (5.0+)
- 🟡 Web (em desenvolvimento)
- 🟡 macOS (em desenvolvimento)

### 🔧 Técnico
- Safe Hive access helpers em `lib/utils/hive_safe.dart`
- Proteção contra NullPointerException em recomendações
- Otimizado carregamento de UI com delays apropriados
- Dispose melhorado para MediaPlayer
- Scripts de build Windows automatizados (PowerShell)
- Flutter 3.38.6+, Dart 3.10.7+
  
---

**Versão anterior:** v1.1.0
**Próxima versão:** v1.3.0 (planejado)
---

**Versão anterior:** v1.1.0
**Data de release:** 14 de fevereiro de 2026
