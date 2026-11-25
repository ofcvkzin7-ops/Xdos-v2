# DENIS XDOS EMULATOR V1

Projeto Android Java/XML com uma interface de desktop simulada em roxo e preto.

## Gerar APK pelo GitHub
1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a branch `main`.
3. Abra a aba **Actions**.
4. Selecione **Build DENIS XDOS APK** e clique em **Run workflow** (ou aguarde o build após enviar o código).
5. Abra a execução concluída e baixe o artefato **DENIS-XDOS-APK**.
6. Dentro do ZIP do artefato estará `app-debug.apk`.

## Observação
Esta V1 é um simulador visual de desktop Android. Ela não executa programas Windows/Linux de PC. Os botões mostram janelas demonstrativas; recursos reais como gerenciador de arquivos, navegador próprio e execução de programas precisam ser implementados separadamente.

## Compatibilidade 32 bits
A configuração de build inclui `armeabi-v7a` para bibliotecas nativas ARM de 32 bits.
O aplicativo desta versão usa Java/XML e não inclui bibliotecas nativas próprias.
Requisito mínimo configurado: Android 6.0 (API 23).

## Compatibilidade 64 bits
Também está configurada a ABI ARM64 `arm64-v8a`, além de ARM 32 bits.
