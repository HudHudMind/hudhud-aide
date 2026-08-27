# HudHud AIDE: Ambiente de Desenvolvimento Inteligente Autônomo

<p align="center">
  <b>Languages:</b> <a href="../README.md">English</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.ar.md">العربية</a> | <a href="README.ja.md">日本語</a> | <a href="README.ru.md">Русский</a> | <a href="README.es.md">Español</a> | <b>Português</b> | <a href="README.zh.md">简体中文</a>
</p>

---

[![Versão](https://img.shields.io/badge/version-v0.4.46-orange.svg)](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46)
[![Plataforma](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)](https://github.com/HudHudMind/hudhudscript)
[![Ferramentas](https://img.shields.io/badge/toolchain-HudHudScript%20x86_64%20(v1..v4)-green.svg)](https://github.com/HudHudMind/hudhudscript)

O **HudHud AIDE** é um ambiente de desenvolvimento integrado projetado principalmente para [**HudHudScript**](https://github.com/HudHudMind/hudhudscript), oferecendo suporte completo à edição de código-fonte e desenvolvimento de projetos em linguagens modernas como **Python, Rust, C/C++ e TypeScript/JavaScript** por meio de seu editor integrado e agente de IA para codificação.

O ambiente une dois fluxos de trabalho complementares:
* **Edição de Código e Assistência de Agente:** Criação, diagnóstico e refatoração de código-fonte multilíngue com um agente de IA ciente do espaço de trabalho.
* **Programação Visual (`.hudhudgraph`):** Um sistema de programação visual baseado em nós para modelar, estruturar e gerar fluxos lógicos nativos de **HudHudScript** e pipelines multiagentes.

O HudHud AIDE conecta o **desenvolvimento de software convencional com paradigmas modernos**:
* **Programação Agêntica (Agentic Programming):** Definição e implantação de agentes autônomos, funções, vinculação de ferramentas e coordenação multiagente.
* **Engenharia de Loops e Cadeias de Loops (Loop Engineering & Loop Chains):** Construção de loops de execução baseados em feedback, ciclos de avaliação e cadeias de refinamento iterativo.
* **Sistemas de Governança (Governance):** Aplicação de restrições operacionais, políticas de segurança, regras de validação e limites de permissão diretamente no código e nos modelos visuais.
* **Programação Orientada ao Sujeito (SOP):** Estruturação de software centrada em sujeitos ativos, contextos operacionais e intenções de comportamento.

Engenheiros e desenvolvedores podem construir agentes de IA personalizados e arquiteturas de sistemas visualmente por meio de programação visual, programaticamente no código-fonte ou em colaboração com o agente de IA integrado.

---

## Visão Geral dos Recursos

```
┌─────────────────────────────────────────────────────────────┐
│                        HudHud AIDE                          │
├───────────────────┬─────────────────────┬───────────────────┤
│Programação Visual │     Agente de IA    │   HudHudScript    │
│  (.hudhudgraph    │ (IA com Contexto do │ (Ambiente Nativo  │
│  Sistema de Nós)  │  Espaço de Trabalho)│   de Execução)    │
└───────────────────┴─────────────────────┴───────────────────┘
```

* **Modelagem Visual de Arquitetura e Lógica:** Modele fluxos de aplicações, pipelines de agentes e estruturas de estado com programação visual baseada em nós.
* **Parceiro de Programação em IA:** Um agente integrado que analisa sua base de código, estrutura do projeto e gráficos visuais.
* **Suporte a Paradigmas do HudHudScript:** Integração nativa para Agentic Programming, Loop Engineering, Governança e Subject-Oriented Programming (SOP).
* **Ferramentas Otimizadas para Hardware:** Compilador, interpretador, LSP e gerenciador de pacotes pré-configurados para sua CPU (`x86-64-v1` to `v4`).

---

## Programação Visual e HudHudGraphs

A **Programação Visual** no HudHud AIDE fornece uma tela interativa para projetar e inspecionar arquiteturas de software e fluxos de trabalho visualmente junto com seu código-fonte.

As arquiteturas visuais são salvas em arquivos padrão **`.hudhudgraph`**.

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

### Recursos:
* **Mais de 240 Tipos de Nós Especializados:** Nós prontos para uso cobrindo fluxos de aplicação, definições de agentes, pipelines de dados, máquinas de estado e regras de governança.
* **Conexões de Pinos Tipadas:** Canais de dados claros e fluxos de execução com validação de pinos segura por tipos.
* **Inspetor de Propriedades:** Selecione qualquer nó para configurar seus parâmetros, comportamento e atributos em tempo real.
* **Fluxo de Trabalho Híbrido:** Use arquivos visuais `.hudhudgraph` junto com o código-fonte `.hud` sem sobrecarga de geração forçada de código.

### Como Usar:
1. Abra ou crie um arquivo `.hudhudgraph` em seu espaço de trabalho.
2. Clique em **"Open with Visual Designer"** na aba do editor.
3. Arraste os nós da **Paleta** esquerda para a tela.
4. Conecte os caminhos de execução e pinos de dados entre os nós.
5. Edite as propriedades no painel direito do inspetor e salve (`Ctrl + S` / `Cmd + S`).

---

## Agente de Codificação IA Integrado

O HudHud AIDE inclui um assistente de IA nativo projetado para operar diretamente em todo o espaço de trabalho do seu projeto.

### Principais Tarefas:
* **Análise do Espaço de Trabalho:** Lê e compreende arquivos-fonte, configurações de projeto e arquiteturas `.hudhudgraph`.
* **Implementação Multi-arquivos:** Implementa recursos e refatorações em vários arquivos em uma única etapa.
* **Diagnóstico e Resolução de Erros:** Identifica avisos de compilador, exceções em tempo de execução e erros de tipo, fornecendo correções verificadas.
* **Automação de Tarefas:** Executa planos de engenharia de várias etapas, testes e migrações de projetos.

---

## Suporte a Linguagem e Paradigmas do HudHudScript

O HudHud AIDE foi projetado para entender e suportar nativamente os paradigmas fundamentais do [**HudHudScript**](https://github.com/HudHudMind/hudhudscript):

* **Programação Agêntica (Agentic Programming):** Estruturas no nível da linguagem para definir agentes autônomos, papéis, responsabilidades, ferramentas e interações multiagentes.
* **Engenharia de Loops (Loop Engineering):** Loops de execução estruturados e orientados a feedback que combinam ações, validações e refinamentos iterativos.
* **Sistemas de Governança (Governance):** Recursos integrados para definir papéis, regras, restrições, conselhos e permissões diretamente no código e nos gráficos.
* **Programação Orientada ao Sujeito (SOP):** Modelagem de software centrada em sujeitos, contextos e responsabilidades comportamentais.

---

## Conjunto de Ferramentas Nativas do HudHudScript

O HudHud AIDE vem com o conjunto completo de ferramentas nativas. Durante a instalação, ele detecta os recursos da CPU (SSE4.2, AVX2, AVX-512) e ativa o conjunto correspondente (`x86-64-v1` to `v4`):

| Ferramenta | Papel |
| :--- | :--- |
| **`hudhud`** | Runtime CLI e executor de aplicações |
| **`hudc`** | Compilador nativo otimizador do HudHudScript |
| **`hudi`** | Shell REPL interativo e interpretador em tempo real |
| **`hudconv`** | Utilitário de migração de AST, bytecode e esquemas |
| **`hudhudscript-lsp`** | Motor LSP para destaque de sintaxe, autocompletar e documentação ao passar o cursor |
| **`hudhud_ffi`** | Runtime de Interface de Funções Estrangeiras (FFI) C / Rust |

---

## Fluxo de Desenvolvimento Unificado

```
   1. Programação Visual     2. Implementação           3. Verificação
 ┌──────────────────┐      ┌──────────────────┐      ┌──────────────────┐
 │ Modelar Gráfico  │ ───► │ Escrever Código  │ ───► │ Compilar, Testar │
 │ (.hudhudgraph)   │      │ com Agente de IA │      │ e Executar       │
 └──────────────────┘      └──────────────────┘      └──────────────────┘
```

1. **Modelar:** Projete sua lógica, agentes ou pipelines visualmente usando a Programação Visual.
2. **Implementar:** Escreva código HudHudScript ou colabore com o Agente de IA para implementar regras de negócio.
3. **Executar e Depurar:** Execute e teste diretamente na IDE usando os utilitários nativos e ferramentas interativas.

---

## Requisitos do Sistema e Instalação

Baixe os pacotes de instalação mais recentes na página [GitHub Releases](https://github.com/HudHudMind/hudhud-aide/releases/tag/v0.4.46) ou através dos links diretos abaixo:

### Windows (x64)
* **SO:** Windows 10 / 11 (64-bit)
* **Download:** [`hudhud-aide-v0.4.46-win-x64-setup.exe`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-win-x64-setup.exe)
* **Aviso do SmartScreen / Binário não assinado:**
  Como o instalador ainda não possui assinatura digital, o Microsoft Defender SmartScreen pode exibir o aviso *"O Windows protegeu o seu PC"*:
  1. Clique em **"Mais informações"** (*More info*).
  2. Clique em **"Executar assim mesmo"** (*Run anyway*) para prosseguir com a instalação.
* *O instalador configura automaticamente o nível de binários ideal para sua CPU (`v1` to `v4`).*

### Linux (x86_64)
* **SO:** Ubuntu 20.04+, Debian 11+, Fedora, Arch Linux, Kali Linux
* **Download:** [`hudhud-aide-v0.4.46-linux-x64-installer.run`](https://github.com/HudHudMind/hudhud-aide/releases/download/v0.4.46/hudhud-aide-v0.4.46-linux-x64-installer.run)
* **Instalação:**
  ```bash
  chmod +x hudhud-aide-v0.4.46-linux-x64-installer.run
  ./hudhud-aide-v0.4.46-linux-x64-installer.run
  ```

---

## Comunidade e Links
 
* **Website:** [https://hudhudscript.com](https://hudhudscript.com)
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

## Licença e Contato

O HudHud AIDE é um ambiente de desenvolvimento profissional desenvolvido pelo **HudHud Script**.

* **Repositório:** [https://github.com/HudHudMind/hudhudscript](https://github.com/HudHudMind/hudhudscript)

---
*© 2026 HudHud Script. Todos os direitos reservados.*
