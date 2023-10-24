# kvtheme

![Alt text](docs/img/prompt-pic.png)

Тема PowerShell для [oh-my-posh](https://ohmyposh.dev/)

## Особенности

-   Розовая: используется розовый цвет
-   Git: отображает информацию о статусе репозитория, когда оболочка находится в нём
-   Transient prompt: заменяет строку оболочки на упрощённый вариант
-   Кроссплатформенность: как и PowerShell, можно использовать на любых OS

## Предварительные требования

-   PowerShell
-   Oh-my-posh

Также не стоит забывать про:

-   Nerd fonts

## Установка

Клонируйте репозиторий

```pwsh
git clone https://github.com/Katy248/kvtheme ~/.themes/powershell
```

Инициализируйте тему

```pwsh
oh-my-posh init pwsh --config ~/.themes/powershell/theme.omp.json | Invoke-Expression
```
