# DENIS XDOS EMULATOR V2.1 - PERFORMANCE

Projeto Android Java/XML com desktop visual simulado em roxo e preto.

## Melhorias V2.1
- Animações de transição de janelas do sistema desativadas para reduzir efeitos visuais.
- Interface simples, sem animações contínuas de ícones.
- Versão do aplicativo atualizada para 2.1.
- Filtros de arquitetura ARM 32/64 bits. O projeto usa Java/XML e não inclui bibliotecas nativas próprias.
- Workflow do GitHub Actions configurado para instalar Gradle 8.9 e compilar o APK.

## Gerar APK pelo GitHub
1. Envie todos os arquivos para a branch `main` ou `master`.
2. Abra **Actions**.
3. Selecione **DENIS XDOS V2.1 - Android APK**.
4. Clique em **Run workflow**.
5. Abra a execução concluída e baixe o artefato **DENIS-XDOS-V2.1-APK**.

O APK estará em `app/build/outputs/apk/debug/app-debug.apk`.

## Limitações
Esta é uma interface de desktop simulada para Android. Não executa programas de Windows/Linux. Os botões de arquivos, navegador, jogos e notas ainda são demonstrativos.

Requisito mínimo configurado: Android 6.0 (API 23).
