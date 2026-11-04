# Concurso — preparação para docência em Matemática

Repositório de estudos para concursos de professor de Matemática, com foco em **UFMT** (magistério superior) e **IFMT** (Ensino Básico, Técnico e Tecnológico).

## Coleção de planos de aula

- [UFMT — 14 planos para provas didáticas universitárias, organizados por edital e campus](UFMT/Planos-de-Aula/README.md). Inclui demonstrações, exemplos e rubricas de autoavaliação.

## Guias em LaTeX

- [UFMT — Guia para concurso docente universitário em Matemática](UFMT/Guias/guia_concurso_docente_matematica_UFMT_2026.tex): análise de edital, prova escrita, prova didática, títulos, demonstrações e preparação de longo prazo.
- [IFMT — Análise de concursos de Matemática e bancas (IFMT/IFC)](IFMT/Guias/analise_concursos_matematica_IFMT_IFC.tex): critérios de prova didática, comparação de bancas, justificativas do IFC, erros frequentes e estratégias de aula.

## Estrutura

```text
Concurso/
├── UFMT/
│   ├── Guias/
│   ├── Editais/
│   ├── Planos-de-Aula/
│   ├── Provas-Escritas/
│   └── Material-de-Estudo/
├── IFMT/
│   ├── Guias/
│   ├── Editais/
│   ├── Planos-de-Aula/
│   └── Material-de-Estudo/
└── Referencias/
```

As pastas ainda sem arquivos serão criadas à medida que novos materiais forem adicionados.

## Compilar os guias

Os arquivos `.tex` são autônomos (não dependem de arquivos locais adicionais). Para gerar o PDF, instale uma distribuição TeX completa e execute duas vezes, dentro da pasta de cada guia:

```bash
pdflatex -interaction=nonstopmode nome_do_arquivo.tex
pdflatex -interaction=nonstopmode nome_do_arquivo.tex
```

Também é possível abrir os arquivos no Overleaf.

**Atenção:** os materiais são estudos independentes, baseados em editais e documentos anteriores. Requisitos e critérios podem mudar; confira sempre o edital oficial e suas retificações antes de se inscrever.
