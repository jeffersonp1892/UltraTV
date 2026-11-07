# UltraTV — Android TV IPTV Player

Projeto inicial nativo Android (Kotlin) com interface horizontal preta/vermelha, navegação por controle remoto, carregamento de listas M3U por URL e reprodução de streams compatíveis via AndroidX Media3/ExoPlayer.

## Requisitos para compilar
- Android Studio recente
- JDK 17
- Android SDK Platform 35

## Gerar APK debug
1. Abra a pasta `UltraTV` no Android Studio.
2. Aguarde a sincronização do Gradle e a instalação das dependências.
3. Selecione **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. O APK será gerado em `app/build/outputs/apk/debug/app-debug.apk`.

Também é possível compilar no terminal com `gradle assembleDebug` (com Gradle instalado).

## Instalar pelo Downloader
O Downloader não hospeda o APK. Depois de gerar o APK, publique-o em um endereço HTTPS direto e estável. No Downloader, use o código criado pelo serviço de encurtamento/hosting para abrir esse endereço e instalar. O código só poderá ser criado depois que o APK estiver hospedado.

## Uso
Abra o UltraTV, cole uma URL M3U/M3U8 autorizada e selecione **Carregar lista**. Depois selecione um canal para reproduzir. Uma URL Xtream Codes pode ser usada quando o provedor fornecer o link M3U (`get.php`) correspondente.

Use somente listas e transmissões que você tenha autorização para acessar. O app não inclui canais, listas, credenciais ou conteúdo de terceiros.
