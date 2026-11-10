# MoveTracker - Chip Rastreador

Site de apresentação do **MoveTracker**, um chip rastreador que envia a localização de veículos, equipamentos e bens para uma plataforma, onde a pessoa acompanha tudo pelo celular ou pelo computador.

O projeto é um site estático, feito apenas com **HTML** e **CSS**, sem JavaScript e sem dependências para instalar.

## Páginas

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Início: apresentação do produto e resumo das telas do aplicativo |
| `produto.html` | O que é o chip e onde usá-lo |
| `como-funciona.html` | O caminho da informação e os passos de uso |
| `aplicativo.html` | Telas do celular e do painel, e como usar cada uma |
| `recursos.html` | Lista de recursos do sistema |
| `contato.html` | Perguntas frequentes e formas de contato |

Todas as páginas usam o mesmo menu de navegação, que também aparece no rodapé. A página atual fica destacada no menu.

## Estrutura de arquivos

```
site/
├── index.html
├── produto.html
├── como-funciona.html
├── aplicativo.html
├── recursos.html
├── contato.html
├── style.css
└── README.md
```

O `style.css` é compartilhado por todas as páginas. Mantenha os arquivos `.html` e o `style.css` na mesma pasta.

## Como executar

1. Baixe ou clone o projeto.
2. Abra o arquivo `index.html` no navegador (clique duas vezes ou use "Abrir com").
3. Navegue pelas páginas usando o menu.

Não é preciso servidor nem instalação. É necessário estar conectado à internet para carregar as fontes e as imagens.

## Tecnologias

- HTML5
- CSS3 (variáveis, Grid, Flexbox e `@media` para responsividade)
- Fontes do [Google Fonts](https://fonts.google.com): Bricolage Grotesque e Figtree
- Imagens do [Unsplash](https://unsplash.com), carregadas por links `https`

## Recursos do site

- Layout responsivo, para celular, tablet e computador
- Telas do aplicativo (mapa, lista de objetos e alertas) e do painel desenhadas só com HTML e CSS
- Perguntas frequentes com `<details>`, sem JavaScript
- Foco visível no teclado e respeito à preferência de reduzir animações

## Como personalizar

**Cores e fontes:** edite as variáveis no começo do `style.css`, na regra `:root`.

```css
:root {
  --floresta: #06402b;
  --ambar: #f5a524;
  --titulo: "Bricolage Grotesque", sans-serif;
}
```

**Imagens:** troque o endereço no atributo `src` de cada `<img>` por outro link `https`. Use sempre um texto descritivo no `alt`.

**Contato:** em `contato.html`, substitua o e-mail, o WhatsApp e o horário de atendimento, que são apenas exemplos.

**Dados das telas:** os nomes, as posições e as porcentagens de bateria mostrados em `aplicativo.html` são ilustrativos.

## Observações

- Se alguma imagem do Unsplash não carregar, troque o link por outro. As imagens têm uma cor de fundo de reserva para o layout não quebrar.
- O site apresenta o produto e não tem login, cadastro nem integração com um sistema real de rastreamento.

## Autor

Projeto desenvolvido por Ronaldo Melo.
