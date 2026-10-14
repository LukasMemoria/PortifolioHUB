# PortifolioHUB

**Área:** desenvolvimento web  
**Tipo:** portfólio acadêmico e pessoal  
**Responsável:** Lucas Bordalo Memoria

## Objetivo

Centralizar a apresentação de projetos acadêmicos e pessoais em um site estático, com uma página pública e documentação organizada no GitHub.

## O que o projeto oferece

- Página inicial com apresentação, seção sobre o autor e lista de projetos.
- Navegação por âncoras entre as seções.
- Cartões com resumo e links para a documentação individual.
- Layout responsivo para telas menores.
- Publicação automática do conteúdo do repositório no GitHub Pages.

## Tecnologias e ferramentas

- **HTML5:** estrutura e conteúdo das páginas.
- **CSS3:** cores, tipografia, layout e adaptação para celular.
- **Git:** histórico de alterações e versionamento.
- **GitHub:** hospedagem do código e revisão de mudanças.
- **GitHub Pages:** publicação do site.
- **GitHub Actions:** automação da implantação a cada atualização da branch `main`.

## Estrutura do projeto

- `index.html`: página principal.
- `assets/css/style.css`: estilos e regras responsivas.
- `projetos/`: documentação dos projetos apresentados.
- `docs/planejamento.md`: propósito e organização do repositório.
- `.github/workflows/pages.yml`: fluxo de publicação do site.
- `README.md`: visão geral e instruções do repositório.

## Como visualizar

Abra [o site publicado](https://lukasmemoria.github.io/PortifolioHUB/) em um navegador. Para visualizar uma cópia local, clone o repositório e abra `index.html):

```bash
git clone https://github.com/LukasMemoria/PortifolioHUB.git
cd PortifolioHUB
```

Não são necessárias dependências ou compilação.

## Publicação

O workflow `.github/workflows/pages.yml` publica a branch `main` no GitHub Pages. O resultado e o histórico das implantações podem ser acompanhados na aba **Actions** do repositório.

## Próximas melhorias

- Incluir capturas de tela e demonstrações dos projetos.
- Acrescentar tecnologias e detalhes de implementação aos projetos quando confirmados.
- Atualizar a documentação junto com novas funcionalidades.
