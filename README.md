# AluraBooks

Projeto front-end de uma vitrine de livros. A página consulta uma lista de livros em uma API, aplica desconto e permite explorar o catálogo por categoria, disponibilidade e preço.

## Funcionalidades

- Carrega os livros da API e exibe capa, título, autor, preço e categoria.
- Aplica desconto de 30% aos preços apresentados inicialmente.
- Filtra o catálogo por livros de front-end, back-end ou dados.
- Mostra apenas os livros disponíveis e calcula o valor total deles.
- Ordena os livros por preço.
- Destaca visualmente os livros indisponíveis.

## Como executar

O projeto não precisa de instalação de dependências ou etapa de build. Como os dados são buscados com `fetch`, abra a página por um servidor local em vez de abrir o arquivo HTML diretamente.

Uma opção é usar a extensão **Live Server** do VS Code:

1. Abra a pasta `livraria` no VS Code.
2. Clique com o botão direito em `index.html`.
3. Selecione **Open with Live Server**.

## Tecnologias

- HTML
- CSS
- JavaScript
- Fetch API

## Organização dos arquivos

```text
livraria/
├── app/
│   ├── main.js             # Busca os livros e inicia a exibição
│   ├── metodoForEach.js    # Monta os cartões de livros na página
│   ├── metodoMap.js        # Aplica desconto aos preços
│   ├── metodoFilter.js     # Filtra livros e calcula o total disponível
│   ├── metodoSort.js       # Ordena livros por preço
│   └── metodoReduce.js     # Soma os preços dos livros disponíveis
├── imagens/                # Logos, banners e capas locais
├── index.html
├── requisicao.txt          # Endereço da API de livros
└── style.css
```

## Fonte dos dados

Os dados do catálogo são obtidos de:

<https://guilhermeonrails.github.io/casadocodigo/livros.json>
