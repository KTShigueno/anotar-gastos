# Anotar gastos

Bloco de notas de gastos para o iPhone, bem simples: **o que foi** e **quanto**. Funciona **sem internet** depois de instalado, e as anotações ficam **só no telemóvel** (nada é enviado para servidores).

No fim da semana ou do mês, o botão **Enviar para o computador** gera um texto, que você manda para você mesmo (AirDrop, e-mail ou WhatsApp) e cola no programa de controle de gastos do computador.

## Resumo (consulta)

Na aba **Resumo**, o app abre o arquivo de dados que o programa do computador guarda na nuvem (`os-meus-gastos.cofre`, criptografado com a sua senha) e mostra, só para consulta, os gastos e entradas do mês, os gastos por categoria com os orçamentos e os lançamentos. A senha e os dados ficam só na memória do telemóvel e são apagados ao fechar o resumo.

## Instalar no iPhone

1. Abra o endereço deste app no **Safari**.
2. Toque em **Partilhar** (o quadrado com a seta) → **Adicionar ao ecrã principal**.
3. A partir daí, abra pelo ícone **Gastos**. Funciona sem internet.

> Se apagar o ícone, as anotações que ainda não foram enviadas se perdem.

## Formato do texto enviado

```
Os Meus Gastos — anotações
23/11/2026 · -12,50 · Farmácia #k3f9a2b
24/11/2026 · +20,00 · Reembolso #k3fb1c4
```

Uma linha por anotação: data, valor (`-` gasto, `+` entrada), descrição e um código que evita duplicados.

## Arquivos

- `index.html` — o app inteiro (HTML, CSS e JavaScript, sem bibliotecas externas)
- `sw.js` — guarda o app no telemóvel para abrir offline
- `manifest.webmanifest`, `icon-*.png` — nome e ícone na tela inicial
