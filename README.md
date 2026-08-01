# Relógio Sempre Visível

Aplicativo Android que exibe um relógio digital flutuante sobre outros aplicativos.

## Recursos

- Relógio HH:mm:ss.
- Sobreposição sobre outros aplicativos.
- Pode ser arrastado pela tela.
- Atualização a cada segundo.
- Serviço em primeiro plano para manter o relógio funcionando.
- Compatível com Android 8.0+ (API 26+).

## Como abrir

1. Abra esta pasta no Android Studio.
2. Aguarde a sincronização do Gradle.
3. Conecte um celular Android ou use um emulador.
4. Execute o projeto.
5. No aplicativo, toque em "Permitir sobreposição".
6. Ative "Permitir exibição sobre outros apps".
7. Volte ao aplicativo e toque em "Ligar relógio".

## Gerar APK

No Android Studio:
Build > Build Bundle(s) / APK(s) > Build APK(s).

O APK de debug normalmente ficará em:
app/build/outputs/apk/debug/app-debug.apk

## Observação

Em alguns fabricantes (Samsung, Xiaomi, Motorola etc.), o sistema pode ter controles próprios de bateria/autoinicialização. Se o relógio for encerrado depois de algum tempo, pode ser necessário permitir que o aplicativo rode em segundo plano.
