# DENIS XDOS V2.5

Projeto Android nativo em Java, com uma interface de desktop simulada em roxo e preto.

## Recursos da V2.5
- Desktop em orientação paisagem com barra inferior e menu Iniciar.
- Atalhos para Arquivos, Navegador, Notas e Configurações.
- Explorador demonstrativo com atalhos para pastas comuns.
- Navegador que abre endereços no navegador instalado no Android.
- Bloco de notas com salvamento durante a sessão atual.
- Pesquisa simples de aplicativos e tela Sobre.
- Android mínimo 6.0 (API 23); código Java sem bibliotecas nativas próprias, compatível com dispositivos ARM 32/64 bits.

## Gerar o APK

### GitHub Actions
1. Envie o conteúdo deste projeto para um repositório GitHub, na branch `main`.
2. Abra a aba **Actions** e execute **DENIS XDOS APK** (ou faça push na `main`).
3. Baixe o artefato `DENIS-XDOS-APK-32-64-BITS` quando a execução terminar.

### Localmente
Com JDK 17, Android SDK (plataforma 35) e Gradle 8.7 ou superior compatível com o Android Gradle Plugin 8.6.1, execute:

```bash
gradle assembleDebug
```

O APK de depuração será gerado em `app/build/outputs/apk/debug/app-debug.apk`.

## Observações
Esta versão é um ambiente desktop simulado, não um sistema operacional independente e não executa programas Windows/Linux. O explorador apresenta atalhos demonstrativos; o acesso real aos arquivos depende de permissões e integração adicional. As notas ficam guardadas apenas durante a sessão atual do aplicativo.
