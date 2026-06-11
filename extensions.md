# VS Code Extensions

Extensões que uso no dia a dia como desenvolvedor fullstack (Vue/Nuxt, .NET, PHP/Laravel) e DevOps.
Cada extensão tem uma descrição curta e o comando de instalação — instale só o que faz sentido para o seu contexto.

---

## Qualidade de Código

| Extensão | ID | Descrição |
|---|---|---|
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | `dbaeumer.vscode-eslint` | Linting JavaScript/TypeScript em tempo real. Indispensável. |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | `esbenp.prettier-vscode` | Formatador de código opinativo. Elimina discussões de estilo no time. |
| [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint) | `stylelint.vscode-stylelint` | Linter para CSS, SCSS e estilos em Vue/HTML. |
| [EditorConfig](https://marketplace.visualstudio.com/items?itemName=editorconfig.editorconfig) | `editorconfig.editorconfig` | Padroniza indent, charset e fim de linha entre editores e devs. |
| [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) | `aaron-bond.better-comments` | Coloriza comentários por tipo: `!` erro, `?` dúvida, `TODO`, etc. |
| [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) | `streetsidesoftware.code-spell-checker` | Corretor ortográfico que entende camelCase e nomes de variáveis. |
| [Spell Checker PT-BR](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese-brazilian) | `streetsidesoftware.code-spell-checker-portuguese-brazilian` | Dicionário português para o Code Spell Checker. |

```bash
code --install-extension dbaeumer.vscode-eslint
code --install-extension esbenp.prettier-vscode
code --install-extension stylelint.vscode-stylelint
code --install-extension editorconfig.editorconfig
code --install-extension aaron-bond.better-comments
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension streetsidesoftware.code-spell-checker-portuguese-brazilian
```

---

## TypeScript & JavaScript

| Extensão | ID | Descrição |
|---|---|---|
| [Pretty TS Errors](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors) | `yoavbls.pretty-ts-errors` | Transforma erros TypeScript incompreensíveis em linguagem humana. |
| [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) | `wix.vscode-import-cost` | Mostra o peso de cada import direto no editor. Consciência de bundle. |
| [NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) | `christian-kohler.npm-intellisense` | Autocomplete de nomes de pacotes npm nos imports. |

```bash
code --install-extension yoavbls.pretty-ts-errors
code --install-extension wix.vscode-import-cost
code --install-extension christian-kohler.npm-intellisense
```

---

## Vue / Nuxt

| Extensão | ID | Descrição |
|---|---|---|
| [Volar](https://marketplace.visualstudio.com/items?itemName=vue.volar) | `vue.volar` | LSP oficial para Vue 3. Autocomplete, tipos, templates. Essencial. |
| [Goto Alias](https://marketplace.visualstudio.com/items?itemName=antfu.goto-alias) | `antfu.goto-alias` | Navega para arquivos por path alias (`@/`, `~/`, etc.) sem configuração extra. |
| [Lit HTML](https://marketplace.visualstudio.com/items?itemName=bierner.lit-html) | `bierner.lit-html` | Syntax highlight para templates `html\`...\`` em arquivos JS/TS com Lit. |
| [Lit Plugin](https://marketplace.visualstudio.com/items?itemName=runem.lit-plugin) | `runem.lit-plugin` | Autocomplete, diagnósticos e type-check para templates Lit/Web Components. |

```bash
code --install-extension vue.volar
code --install-extension antfu.goto-alias
code --install-extension bierner.lit-html
code --install-extension runem.lit-plugin
```

---

## PHP / Laravel

| Extensão | ID | Descrição |
|---|---|---|
| [Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client) | `bmewburn.vscode-intelephense-client` | Melhor LSP PHP disponível. Autocomplete, tipos, navegação. |
| [PHP Tools](https://marketplace.visualstudio.com/items?itemName=devsense.phptools-vscode) | `devsense.phptools-vscode` | Debug, test runner e features avançadas complementares ao Intelephense. |
| [PHP CS Fixer](https://marketplace.visualstudio.com/items?itemName=junstyle.php-cs-fixer) | `junstyle.php-cs-fixer` | Formatador PHP automático com suporte a PSR-2/PSR-12. |
| [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=mehedidracula.php-namespace-resolver) | `mehedidracula.php-namespace-resolver` | Auto-import e organização de `use` statements. |
| [XDebug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug) | `xdebug.php-debug` | Debug PHP passo a passo integrado ao VS Code. |
| [PHP CodeSniffer](https://marketplace.visualstudio.com/items?itemName=johnrdorazio.vscode-phpcs) | `johnrdorazio.vscode-phpcs` | Relatório de violações de padrão sem auto-fix. Útil em CI. |
| [Composer PHP](https://marketplace.visualstudio.com/items?itemName=devsense.composer-php-vscode) | `devsense.composer-php-vscode` | Integração com Composer direto no editor. |
| [PHP Profiler](https://marketplace.visualstudio.com/items?itemName=devsense.profiler-php-vscode) | `devsense.profiler-php-vscode` | Profiling de performance PHP integrado. |
| [Laravel Blade Spacer](https://marketplace.visualstudio.com/items?itemName=austenc.laravel-blade-spacer) | `austenc.laravel-blade-spacer` | Formata automaticamente espaços em diretivas Blade `{{ }}`. |

```bash
code --install-extension bmewburn.vscode-intelephense-client
code --install-extension devsense.phptools-vscode
code --install-extension junstyle.php-cs-fixer
code --install-extension mehedidracula.php-namespace-resolver
code --install-extension xdebug.php-debug
code --install-extension johnrdorazio.vscode-phpcs
code --install-extension devsense.composer-php-vscode
code --install-extension devsense.profiler-php-vscode
code --install-extension austenc.laravel-blade-spacer
```

---

## .NET / C#

| Extensão | ID | Descrição |
|---|---|---|
| [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) | `ms-dotnettools.csdevkit` | Suite completa Microsoft para desenvolvimento .NET no VS Code. |
| [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) | `ms-dotnettools.csharp` | LSP C#. Base do Dev Kit — instale os dois. |
| [.NET Runtime](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-runtime) | `ms-dotnettools.vscode-dotnet-runtime` | Dependência interna do C# e Dev Kit. Necessária. |
| [.NET Solution Explorer](https://marketplace.visualstudio.com/items?itemName=fernandoescolar.vscode-solution-explorer) | `fernandoescolar.vscode-solution-explorer` | Painel para navegar em arquivos `.sln` igual ao Visual Studio. |

```bash
code --install-extension ms-dotnettools.csdevkit
code --install-extension ms-dotnettools.csharp
code --install-extension ms-dotnettools.vscode-dotnet-runtime
code --install-extension fernandoescolar.vscode-solution-explorer
```

---

## Git

| Extensão | ID | Descrição |
|---|---|---|
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | `eamodio.gitlens` | O mais completo. Blame inline, histórico por linha, comparações entre branches. |
| [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) | `mhutchie.git-graph` | Visualização gráfica do histórico de branches. Mais visual que o GitLens. |
| [Git Stash](https://marketplace.visualstudio.com/items?itemName=arturock.gitstash) | `arturock.gitstash` | Interface visual para gerenciar stashes do Git. |
| [Git Patch](https://marketplace.visualstudio.com/items?itemName=paragdiwan.gitpatch) | `paragdiwan.gitpatch` | Cria e aplica patches Git diretamente pelo editor. |

```bash
code --install-extension eamodio.gitlens
code --install-extension mhutchie.git-graph
code --install-extension arturock.gitstash
code --install-extension paragdiwan.gitpatch
```

---

## DevOps & Infraestrutura

| Extensão | ID | Descrição |
|---|---|---|
| [GitHub Actions](https://marketplace.visualstudio.com/items?itemName=github.vscode-github-actions) | `github.vscode-github-actions` | Syntax highlight, autocomplete e validação de workflows `.yml`. |
| [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) | `ms-azuretools.vscode-docker` | Gerencia containers, imagens e compose direto no VS Code. |
| [Containers](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-containers) | `ms-azuretools.vscode-containers` | Visão dedicada de containers em execução, separada da extensão Docker. |
| [YAML (Red Hat)](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) | `redhat.vscode-yaml` | Validação e schema YAML. Essencial para configs Docker/CI. |
| [Sync Env](https://marketplace.visualstudio.com/items?itemName=dongido.sync-env) | `dongido.sync-env` | Sincroniza `.env` com `.env.example` automaticamente. |

```bash
code --install-extension github.vscode-github-actions
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-azuretools.vscode-containers
code --install-extension redhat.vscode-yaml
code --install-extension dongido.sync-env
```

---

## Desenvolvimento Remoto

| Extensão | ID | Descrição |
|---|---|---|
| [Remote SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh) | `ms-vscode-remote.remote-ssh` | Edita arquivos em servidores remotos via SSH como se fossem locais. |
| [Remote SSH Edit](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh-edit) | `ms-vscode-remote.remote-ssh-edit` | Complemento para editar configs SSH. |
| [Remote WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl) | `ms-vscode-remote.remote-wsl` | Desenvolvimento dentro do WSL no Windows. |
| [Remote Explorer](https://marketplace.visualstudio.com/items?itemName=ms-vscode.remote-explorer) | `ms-vscode.remote-explorer` | Painel visual para gerenciar conexões remotas (SSH, WSL, containers). |
| [Remote Repositories](https://marketplace.visualstudio.com/items?itemName=ms-vscode.remote-repositories) | `ms-vscode.remote-repositories` | Abre repositórios GitHub diretamente sem clonar localmente. |

```bash
code --install-extension ms-vscode-remote.remote-ssh
code --install-extension ms-vscode-remote.remote-ssh-edit
code --install-extension ms-vscode-remote.remote-wsl
code --install-extension ms-vscode.remote-explorer
code --install-extension ms-vscode.remote-repositories
```

---

## Produtividade

| Extensão | ID | Descrição |
|---|---|---|
| [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) | `christian-kohler.path-intellisense` | Autocomplete de caminhos de arquivo nos imports. |
| [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) | `formulahendry.auto-rename-tag` | Renomeia tag de abertura e fechamento juntas (HTML, Vue, JSX). |
| [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) | `naumovs.color-highlight` | Visualiza cores inline em qualquer tipo de arquivo. |
| [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) | `mechatroner.rainbow-csv` | Coloriza colunas de arquivos CSV para leitura fácil. |
| [XML Tools](https://marketplace.visualstudio.com/items?itemName=dotjoshjohnson.xml) | `dotjoshjohnson.xml` | Formatação, validação e XPath para arquivos XML. |
| [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) | `yzhang.markdown-all-in-one` | Preview, TOC automático e atalhos para Markdown. |
| [WakaTime](https://marketplace.visualstudio.com/items?itemName=wakatime.vscode-wakatime) | `wakatime.vscode-wakatime` | Rastreamento de tempo de codificação por projeto e linguagem. |
| [Jest](https://marketplace.visualstudio.com/items?itemName=orta.vscode-jest) | `orta.vscode-jest` | Runner Jest integrado com feedback visual inline nos testes. |

```bash
code --install-extension christian-kohler.path-intellisense
code --install-extension formulahendry.auto-rename-tag
code --install-extension naumovs.color-highlight
code --install-extension mechatroner.rainbow-csv
code --install-extension dotjoshjohnson.xml
code --install-extension yzhang.markdown-all-in-one
code --install-extension wakatime.vscode-wakatime
code --install-extension orta.vscode-jest
```

---

## Aparência

| Extensão | ID | Descrição |
|---|---|---|
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=pkief.material-icon-theme) | `pkief.material-icon-theme` | Ícones no explorer por tipo de arquivo. Qualidade de vida pura. |
| [Ballerini Theme](https://marketplace.visualstudio.com/items?itemName=balleriniserver.ballerini-theme) | `balleriniserver.ballerini-theme` | Tema de cor escuro com bom contraste. |
| [Language Pack PT-BR](https://marketplace.visualstudio.com/items?itemName=ms-ceintl.vscode-language-pack-pt-br) | `ms-ceintl.vscode-language-pack-pt-br` | Interface do VS Code em português. |

```bash
code --install-extension pkief.material-icon-theme
code --install-extension balleriniserver.ballerini-theme
code --install-extension ms-ceintl.vscode-language-pack-pt-br
```

---

## Integrações

| Extensão | ID | Descrição |
|---|---|---|
| [Claude Code](https://marketplace.visualstudio.com/items?itemName=anthropic.claude-code) | `anthropic.claude-code` | IA da Anthropic integrada ao editor para geração e revisão de código. |
| [Atlassian](https://marketplace.visualstudio.com/items?itemName=atlassian.atlascode) | `atlassian.atlascode` | Jira e Confluence dentro do VS Code. Cria e atualiza issues sem sair do editor. |
| [PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.powershell) | `ms-vscode.powershell` | Suporte completo a scripts PowerShell. Essencial no Windows. |

```bash
code --install-extension anthropic.claude-code
code --install-extension atlassian.atlascode
code --install-extension ms-vscode.powershell
```

---

## Instalar tudo de uma vez

Copie e cole no terminal (PowerShell):

```powershell
$extensions = @(
  "aaron-bond.better-comments",
  "antfu.goto-alias",
  "anthropic.claude-code",
  "arturock.gitstash",
  "atlassian.atlascode",
  "austenc.laravel-blade-spacer",
  "balleriniserver.ballerini-theme",
  "bierner.lit-html",
  "bmewburn.vscode-intelephense-client",
  "christian-kohler.npm-intellisense",
  "christian-kohler.path-intellisense",
  "dbaeumer.vscode-eslint",
  "devsense.composer-php-vscode",
  "devsense.phptools-vscode",
  "devsense.profiler-php-vscode",
  "dongido.sync-env",
  "dotjoshjohnson.xml",
  "eamodio.gitlens",
  "editorconfig.editorconfig",
  "esbenp.prettier-vscode",
  "fernandoescolar.vscode-solution-explorer",
  "formulahendry.auto-rename-tag",
  "github.vscode-github-actions",
  "johnrdorazio.vscode-phpcs",
  "junstyle.php-cs-fixer",
  "mechatroner.rainbow-csv",
  "mehedidracula.php-namespace-resolver",
  "mhutchie.git-graph",
  "ms-azuretools.vscode-containers",
  "ms-azuretools.vscode-docker",
  "ms-ceintl.vscode-language-pack-pt-br",
  "ms-dotnettools.csdevkit",
  "ms-dotnettools.csharp",
  "ms-dotnettools.vscode-dotnet-runtime",
  "ms-vscode-remote.remote-ssh",
  "ms-vscode-remote.remote-ssh-edit",
  "ms-vscode-remote.remote-wsl",
  "ms-vscode.powershell",
  "ms-vscode.remote-explorer",
  "ms-vscode.remote-repositories",
  "naumovs.color-highlight",
  "orta.vscode-jest",
  "paragdiwan.gitpatch",
  "pkief.material-icon-theme",
  "redhat.vscode-yaml",
  "runem.lit-plugin",
  "streetsidesoftware.code-spell-checker",
  "streetsidesoftware.code-spell-checker-portuguese-brazilian",
  "stylelint.vscode-stylelint",
  "vue.volar",
  "wakatime.vscode-wakatime",
  "wix.vscode-import-cost",
  "xdebug.php-debug",
  "yoavbls.pretty-ts-errors",
  "yzhang.markdown-all-in-one"
)
$extensions | ForEach-Object { code --install-extension $_ }
```

Ou no bash (Mac/Linux):

```bash
extensions=(
  "aaron-bond.better-comments"
  "antfu.goto-alias"
  "anthropic.claude-code"
  "arturock.gitstash"
  "atlassian.atlascode"
  "austenc.laravel-blade-spacer"
  "balleriniserver.ballerini-theme"
  "bierner.lit-html"
  "bmewburn.vscode-intelephense-client"
  "christian-kohler.npm-intellisense"
  "christian-kohler.path-intellisense"
  "dbaeumer.vscode-eslint"
  "devsense.composer-php-vscode"
  "devsense.phptools-vscode"
  "devsense.profiler-php-vscode"
  "dongido.sync-env"
  "dotjoshjohnson.xml"
  "eamodio.gitlens"
  "editorconfig.editorconfig"
  "esbenp.prettier-vscode"
  "fernandoescolar.vscode-solution-explorer"
  "formulahendry.auto-rename-tag"
  "github.vscode-github-actions"
  "johnrdorazio.vscode-phpcs"
  "junstyle.php-cs-fixer"
  "mechatroner.rainbow-csv"
  "mehedidracula.php-namespace-resolver"
  "mhutchie.git-graph"
  "ms-azuretools.vscode-containers"
  "ms-azuretools.vscode-docker"
  "ms-ceintl.vscode-language-pack-pt-br"
  "ms-dotnettools.csdevkit"
  "ms-dotnettools.csharp"
  "ms-dotnettools.vscode-dotnet-runtime"
  "ms-vscode-remote.remote-ssh"
  "ms-vscode-remote.remote-ssh-edit"
  "ms-vscode-remote.remote-wsl"
  "ms-vscode.powershell"
  "ms-vscode.remote-explorer"
  "ms-vscode.remote-repositories"
  "naumovs.color-highlight"
  "orta.vscode-jest"
  "paragdiwan.gitpatch"
  "pkief.material-icon-theme"
  "redhat.vscode-yaml"
  "runem.lit-plugin"
  "streetsidesoftware.code-spell-checker"
  "streetsidesoftware.code-spell-checker-portuguese-brazilian"
  "stylelint.vscode-stylelint"
  "vue.volar"
  "wakatime.vscode-wakatime"
  "wix.vscode-import-cost"
  "xdebug.php-debug"
  "yoavbls.pretty-ts-errors"
  "yzhang.markdown-all-in-one"
)
for ext in "${extensions[@]}"; do code --install-extension "$ext"; done
```
