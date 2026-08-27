# HudHud AIDE: Entorno de Desarrollo Inteligente Autónomo

<p align="center">
  <b>Languages:</b> <a href="../README.md">English</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.ar.md">العربية</a> | <a href="README.ja.md">日本語</a> | <a href="README.ru.md">Русский</a> | <b>Español</b> | <a href="README.pt.md">Português</a> | <a href="README.zh.md">简体中文</a>
</p>

---

[![Versión](https://img.shields.io/badge/version-v0.4.46-orange.svg)](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46)
[![Plataforma](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)](https://github.com/HudHudMind/hudhudscript)
[![Herramientas](https://img.shields.io/badge/toolchain-HudHudScript%20x86_64%20(v1..v4)-green.svg)](https://github.com/HudHudMind/hudhudscript)

**HudHud AIDE** es un entorno de desarrollo integrado diseñado principalmente para [**HudHudScript**](https://github.com/HudHudMind/hudhudscript), que también admite la edición de código fuente y el desarrollo de proyectos en lenguajes modernos como **Python, Rust, C/C++ y TypeScript/JavaScript** a través de su editor integrado y su agente de programación IA.

El entorno combina dos flujos de trabajo complementarios:
* **Edición de Código y Asistencia de Agente:** Creación, diagnóstico y refactorización de código fuente multilenguaje con un agente de IA consciente del espacio de trabajo.
* **Programación Visual (`.hudhudgraph`):** Un sistema de programación visual basado en nodos para modelar, estructurar y generar flujos lógicos nativos de **HudHudScript** y canalizaciones multiagente.

HudHud AIDE une el **desarrollo de software convencional con paradigmas modernos**:
* **Programación Agéntica (Agentic Programming):** Definición y despliegue de agentes autónomos, roles, vinculación de herramientas y coordinación multiagente.
* **Ingeniería de Bucles y Cadenas de Bucles (Loop Engineering & Loop Chains):** Construcción de bucles de ejecución basados en retroalimentación, ciclos de evaluación y cadenas de refinamiento iterativo.
* **Sistemas de Gobernanza (Governance):** Aplicación de restricciones operativas, políticas de seguridad, reglas de validación y límites de permisos directamente en el código y en los modelos gráficos.
* **Programación Orientada al Sujeto (SOP):** Estructuración de software centrada en sujetos activos, contextos operativos e intenciones de comportamiento.

Los ingenieros y desarrolladores pueden crear agentes de IA personalizados y arquitecturas de sistemas visualmente mediante programación visual, programáticamente en código fuente o en colaboración con el agente de programación integrado.

---

## Capacidades Principales

```
┌─────────────────────────────────────────────────────────────┐
│                        HudHud AIDE                          │
├───────────────────┬─────────────────────┬───────────────────┤
│Programación Visual│    Agente de IA     │   HudHudScript    │
│  (.hudhudgraph    │ (IA con Contexto de │ (Entorno de Ejec. │
│ Sistema de Nodos) │ Espacio de Trabajo) │   Optimizado)     │
└───────────────────┴─────────────────────┴───────────────────┘
```

* **Modelado Visual de Arquitectura y Lógica:** Modele flujos de aplicaciones, canalizaciones de agentes y estructuras de estado con programación visual basada en nodos.
* **Programación en Pareja con IA Autónoma:** Un agente de codificación integrado que analiza el código fuente, la estructura del proyecto y los gráficos visuales.
* **Soporte de Paradigmas de HudHudScript:** Integración nativa de Agentic Programming, Loop Engineering, Governance y Subject-Oriented Programming (SOP).
* **Conjunto de Herramientas Optimizado para Hardware:** Compilador, intérprete, LSP y administrador de paquetes preconfigurados para su CPU (`x86-64-v1` to `v4`).

---

## Programación Visual y HudHudGraphs

La **Programación Visual** en HudHud AIDE ofrece un lienzo interactivo para diseñar e inspeccionar arquitecturas de software y flujos de trabajo de forma visual junto con su código fuente.

Las arquitecturas visuales se guardan en archivos estándar **`.hudhudgraph`**.

```
                    ┌─────────────────────────┐
                    │       Agent Node        │
                    ├───────────┬─────────────┤
                    │ Role      │ Governance  │
                    │ Tools     │ Validation  │
                    └─────┬─────┴──────┬──────┘
                          │            │
                          ▼            ▼
                   [ Action / Loop ] [ Policy ]
```

### Capacidades:
* **Más de 240 Tipos de Nodos Especializados:** Nodos listos para usar que cubren flujo de aplicaciones, definiciones de agentes, canalizaciones de datos, máquinas de estado y reglas de gobernanza.
* **Conexiones de Pines Tipadas:** Canales de datos y flujos de ejecución claros con validación de pines de tipos seguros.
* **Inspector de Propiedades:** Seleccione cualquier nodo para configurar sus parámetros, comportamiento y atributos en tiempo real.
* **Flujo de Trabajo Híbrido:** Utilice archivos visuales `.hudhudgraph` junto con código fuente `.hud` sin sobrecarga forzada de generación de código.

### Modo de Uso:
1. Abra o cree cualquier archivo `.hudhudgraph` en su espacio de trabajo.
2. Haga clic en **"Open with Visual Designer"** en la pestaña del editor.
3. Arrastre nodos desde la **Paleta** izquierda al lienzo.
4. Conecte rutas de ejecución y pines de datos entre nodos.
5. Edite las propiedades en el panel inspector derecho y guarde (`Ctrl + S` / `Cmd + S`).

---

## Agente de Programación IA Integrado

HudHud AIDE incluye un asistente de codificación de IA diseñado para operar directamente en el espacio de trabajo de su proyecto.

### Tareas Principales:
* **Análisis del Espacio de Trabajo:** Lee y comprende archivos de origen, configuraciones de proyecto y arquitecturas `.hudhudgraph`.
* **Implementación Multifichero:** Implementa funciones y refactorizaciones en múltiples archivos en un solo paso.
* **Diagnóstico y Corrección de Errores:** Localiza advertencias de compilador, excepciones de tiempo de ejecución y errores de tipos, ofreciendo correcciones verificadas.
* **Automatización de Tareas:** Sigue planes de ingeniería de múltiples pasos, ejecuciones de pruebas y migraciones de proyectos.

---

## Soporte de Lenguaje y Paradigmas de HudHudScript

HudHud AIDE está diseñado para comprender y respaldar de forma nativa los paradigmas de [**HudHudScript**](https://github.com/HudHudMind/hudhudscript):

* **Programación Agéntica (Agentic Programming):** Estructuras a nivel de lenguaje para definir agentes autónomos, roles, herramientas y coordinación multiagente.
* **Ingeniería de Bucles (Loop Engineering):** Bucles de ejecución estructurados y basados en retroalimentación que combinan acciones, validaciones y refinamiento iterativo.
* **Sistemas de Gobernanza (Governance):** Construcciones integradas para definir roles, reglas, restricciones, consejos y permisos en código y gráficos.
* **Programación Orientada al Sujeto (SOP):** Modelado de software centrado en sujetos activos, contextos y responsabilidades de comportamiento.

---

## Conjunto de Herramientas Nativas de HudHudScript

HudHud AIDE incluye el conjunto completo de herramientas nativas. Durante la instalación, detecta las características de su CPU (SSE4.2, AVX2, AVX-512) y activa los binarios correspondientes (`x86-64-v1` to `v4`):

| Herramienta | Función |
| :--- | :--- |
| **`hudhud`** | Entorno de ejecución CLI y ejecutor de aplicaciones |
| **`hudc`** | Compilador optimizador nativo de HudHudScript |
| **`hudi`** | Shell REPL interactivo e intérprete en vivo |
| **`hudconv`** | Utilidad de migración de AST, bytecode y esquemas |
| **`hudhudscript-lsp`** | Motor LSP para resaltado de sintaxis, autocompletado y documentación al pasar el cursor |
| **`hudhud_ffi`** | Entorno de ejecución de Interfaz de Funciones Foráneas (FFI) C / Rust |

---

## Flujo de Desarrollo Unificado

```
   1. Programación Visual    2. Implementación          3. Verificación
 ┌──────────────────┐      ┌──────────────────┐      ┌──────────────────┐
 │ Modelar Gráfico  │ ───► │ Escribir Código  │ ───► │ Compilar, Probar │
 │ (.hudhudgraph)   │      │ con Agente IA    │      │ y Ejecutar       │
 └──────────────────┘      └──────────────────┘      └──────────────────┘
```

1. **Modelar:** Diseñe su lógica, agentes o canalizaciones de datos visualmente mediante Programación Visual.
2. **Implementar:** Escriba código HudHudScript o colabore con el Agente de IA integrado para implementar la lógica de negocio.
3. **Ejecutar y Depurar:** Ejecute y pruebe directamente en el IDE utilizando las herramientas nativas y de depuración interactiva.

---

## Requisitos del Sistema e Instalación

Descargue los paquetes de instalación más recientes desde [GitHub Releases](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46) o mediante los enlaces directos a continuación:

### Windows (x64)
* **SO:** Windows 10 / 11 (64-bit)
* **Descargar:** [`hudhud-aide-v0.4.46-win-x64-setup.exe`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-win-x64-setup.exe)
* **Aviso de SmartScreen / Binario no firmado:**
  Dado que el instalador actualmente no cuenta con firma digital, Microsoft Defender SmartScreen puede mostrar el aviso *"Windows protegió su PC"*:
  1. Haga clic en **"Más información"** (*More info*).
  2. Haga clic en **"Ejecutar de todas formas"** (*Run anyway*) para continuar con la instalación.
* *El instalador configura automáticamente el nivel óptimo de binarios de CPU (`v1` to `v4`).*

### Linux (x86_64)
* **SO:** Ubuntu 20.04+, Debian 11+, Fedora, Arch Linux, Kali Linux
* **Descargar:** [`hudhud-aide-v0.4.46-linux-x64-installer.run`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-linux-x64-installer.run)
* **Instalación:**
  ```bash
  chmod +x hudhud-aide-v0.4.46-linux-x64-installer.run
  ./hudhud-aide-v0.4.46-linux-x64-installer.run
  ```

---

## Comunidad y Enlaces
 
* **Sitio Web:** [https://hudhudscript.com](https://hudhudscript.com)
* **GitHub (HudHudScript):** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)
* **GitHub (HudHud AIDE):** [https://github.com/HudHudMind/hudhud-aide](https://github.com/HudHudMind/hudhud-aide)
* **Discord:** [https://discord.gg/UxEJ5MfH](https://discord.gg/UxEJ5MfH)
* **Reddit:** [https://www.reddit.com/r/hudhudscript/](https://www.reddit.com/r/hudhudscript/)
* **Twitter / X:** [https://x.com/hudhud_script](https://x.com/hudhud_script)
* **Instagram:** [https://www.instagram.com/hudhudscript/](https://www.instagram.com/hudhudscript/)
* **TikTok:** [https://www.tiktok.com/@hudhudscript](https://www.tiktok.com/@hudhudscript)
* **YouTube:** [https://www.youtube.com/@HudHudScripting](https://www.youtube.com/@HudHudScripting)
* **LinkedIn:** [https://www.linkedin.com/groups/27050016/](https://www.linkedin.com/groups/27050016/)
* **Patreon:** [https://www.patreon.com/cw/hudhudscript](https://www.patreon.com/cw/hudhudscript)

---

## Licencia y Contacto

HudHud AIDE es un entorno de desarrollo profesional desarrollado por **HudHud Script**.

* **Repositorio:** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)

---
*© 2026 HudHud Script. Todos los derechos reservados.*
