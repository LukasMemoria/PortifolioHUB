# PortifolioHUB

Portfólio acadêmico e pessoal de **Lucas Bordalo Memoria**, estudante de Ciência da Computação no CEUB Taguatinga. O site apresenta projetos e documenta sua evolução na área de tecnologia.

## Acesse

- **Site:** [LukasMemoria.github.io/PortifolioHUB](https://lukasmemoria.github.io/PortifolioHUB/)
- **Repositório:** [github.com/LukasMemoria/PortifolioHUB](https://github.com/LukasMemoria/PortifolioHUB)

> Se o site ainda não estiver publicado, aguarde a conclusão do primeiro fluxo de implantação em **Actions** e confira a configuração de **Settings → Pages**.

## Estrutura

```text
.
├── assets/
│   └── css/
│       └── style.css
├── docs/
│   └── planejamento.md
├── projetos/
│   ├── ecogrow/
│   │   └── README.md
│   └── portifoliohub/
│       └── README.md
├── .github/
│   └── workflows/
│       └── pages.yml
├── index.html
└── README.md
```

## Projetos

- [EcoGrow](projetos/ecogrow/README.md) — sistema IoT para monitoramento agrícola.
- [PortifolioHUB](projetos/portifoliohub/README.md) — página de portfólio publicada com GitHub Pages.
- [Planejamento do repositório](docs/planejamento.md) — organização e próximos passos.

## Desenvolvimento local

Abra `index.html` no navegador. O site usa HTML e CSS sem dependências ou etapa de compilação.

## Versionamento

As alterações do projeto são registradas no histórico do GitHub. Para contribuir localmente:

```bash
git clone https://github.com/LukasMemoria/PortifolioHUB.git
cd PortifolioHUB
```

Crie uma branch para cada mudança, escreva mensagens de commit que resumam a alteração e revise o diff antes de enviar.

## Publicação

O workflow em `.github/workflows/pages.yml` publica o conteúdo da branch `main` no GitHub Pages. Em **Settings → Pages**, selecione **GitHub Actions** como origem se ainda não estiver configurada. A URL do site ficará disponível em **Settings → Pages** após a primeira implantação bem-sucedida.

## Tecnologias

HTML5 · CSS3 · Git · GitHub Pages
