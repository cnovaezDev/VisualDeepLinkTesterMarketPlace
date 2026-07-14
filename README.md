Visual Deep Link & Intent Tester

Un plugin para Android Studio que facilita la prueba de Deep Links e Intents en dispositivos conectados mediante ADB.
Características

    Detección Automática: Detecta automáticamente los dispositivos conectados vía ADB.
    Ejecución Visual: Permite disparar Intents con Deep Links sin necesidad de usar la terminal.
    Interfaz Intuitiva: Implementado con Kotlin UI DSL v2 para una experiencia nativa dentro de Android Studio.
    Log de Salida: Muestra la respuesta de ADB en tiempo real.

Roadmap del Proyecto

    Fase 1: Configuración base con Gradle y plugin.xml.
    Fase 2: Esqueleto de la UI (ToolWindow) usando Kotlin UI DSL v2.
    Fase 3: Detección de dispositivos mediante ADB.
    Fase 4: Lógica de ejecución de Intents (comando adb shell am start).
    [-] Fase 5: Persistencia del historial (últimos 10-15 URIs) e integración con GitHub.

Cómo usarlo

    Abre la herramienta "Visual Deep Link Tester" en la barra lateral.
    Selecciona un dispositivo conectado de la lista desplegable.
    Ingresa tu Deep Link en el campo de texto.
    Presiona "Fire Intent" para ejecutar el comando.
    Los resultados se mostrarán en el Log de salida.
