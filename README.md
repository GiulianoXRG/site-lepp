# Site do LEPP

Código da página do **LEPP – Laboratório de Estimativas e Projeções Populacionais**, do Programa de Pós-Graduação em Demografia (PPGDem) da UFRN, publicada no WordPress.

## Arquivos

| Arquivo | O que é | Onde colar no WordPress |
|---|---|---|
| [`LEPP_bloco_wordpress.html`](LEPP_bloco_wordpress.html) | Conteúdo da página (bloco HTML personalizado) | Editor da página → bloco **HTML personalizado** (ou editor de código) |
| [`LEPP_css_adicional.css`](LEPP_css_adicional.css) | Estilos da página, todos limitados a `#lepp-page` | **Aparência → Personalizar → CSS adicional** |

## Seções da página

- Apresentação
- Linhas de pesquisa
- Equipe (pesquisadores, doutorado, mestrado, iniciação científica)
- Projetos de pesquisa (em andamento e concluídos)
- Publicações (organizadas por ano)

Trechos marcados com a classe `pending` (fundo amarelo) são textos que ainda dependem de informação da coordenação.

## Como atualizar o site

1. Edite os arquivos deste repositório.
2. Cole o conteúdo de `LEPP_bloco_wordpress.html` no bloco HTML da página.
3. Cole o conteúdo de `LEPP_css_adicional.css` no CSS adicional do tema.
4. Salve as alterações no Git:

```bash
git add .
git commit -m "descreva a alteração"
git push
```

## Observações

- Todo o CSS é escopado em `#lepp-page`, para não interferir no restante do tema do WordPress.
- Os contadores do topo (pesquisadores, estudantes, projetos e publicações) usam o atributo `data-count` com seletores dos itens das listas.
