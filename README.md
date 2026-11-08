# Portfólio Acadêmico — Eduardo Kuwahara Junior

Portfólio acadêmico desenvolvido com HTML e CSS, organizado no formato de páginas estáticas em `docs/` para publicação no GitHub Pages.

## Estrutura do projeto

```text
Portifólio 6/
├── docs/
│   ├── index.html
│   ├── informacoes.html
│   ├── projetos.html
│   ├── asset/
│   │   └── profile.jpg
│   └── css/
│       ├── style-home.css
│       ├── style-informacoes.css
│       └── style-projetos.css
├── index.html           # redireciona para docs/index.html
├── package.json
├── .nojekyll
└── README.md
```

## Páginas

- `docs/index.html` — apresentação inicial.
- `docs/projetos.html` — projetos acadêmicos com detalhamento completo.
- `docs/informacoes.html` — dados pessoais, formação, experiência, currículo, skills e contato.

## Execução local

Na raiz do projeto:

```bash
python -m http.server 8000
```

Abra:

```text
http://localhost:8000/
```

## Publicação no GitHub Pages

1. Faça push da branch `main`.
2. No GitHub, abra **Settings > Pages**.
3. Em **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/docs`
4. Salve e aguarde a publicação.

URL esperada:

```text
https://fatec-sjc-dsm-portfolio.github.io/ra1461392411030/
```
