# Documentação Técnica

## Visão geral
A página foi desenvolvida como um trabalho acadêmico para apresentar o panorama do mercado de tecnologia. Ela reúne informações sobre vagas locais e nacionais, destacando as principais tecnologias exigidas e as competências que mais aparecem nas oportunidades analisadas.

## Objetivo do projeto
O objetivo principal foi criar uma apresentação visualmente clara, com linguagem mais direta e fácil de acompanhar. A ideia foi comparar o mercado regional com o cenário nacional, além de mostrar como certas ferramentas e habilidades se repetem em diferentes oportunidades.

## Tecnologias e recursos utilizados
- HTML5, para estruturar a página de forma semântica.
- CSS3, para a estilização visual e ajustes de layout.
- Bootstrap 5.3.8, para organização dos elementos e responsividade.
- Arquivo institucional da Univille em `assets/images/univille.png`.
- Git, para controle do versionamento local.
- GitHub Actions, para preparar o deploy no GitHub Pages.

## Estrutura dos arquivos
```text
assets/
  css/style.css
  images/univille.png
index.html
README.md
docs/
  documentacao-tecnica.md
  testes-evidencias.md
```

## Organização da página
A estrutura da página foi pensada para facilitar a leitura e a navegação entre as partes do conteúdo. As principais seções são:
- cabeçalho
- apresentação inicial
- visão geral do estudo
- vagas analisadas
- tecnologias mais citadas
- gráficos e estatísticas
- síntese final
- rodapé

Essa organização ajuda a manter uma sequência lógica e deixa a apresentação mais profissional.

## Responsividade
A interface foi ajustada para funcionar em desktop, tablet e celular. Os principais itens ajustados foram:
- tamanho das fontes;
- espaçamento entre blocos;
- tamanho e alinhamento dos cards;
- organização dos elementos em telas menores.

## Metadados e acessibilidade
No arquivo HTML, foram definidos elementos importantes como:
- charset UTF-8;
- viewport responsivo;
- descrição da página;
- autor do conteúdo;
- título da página;

Esses ajustes deixam a página mais adequada para navegação e apresentação correta em diferentes dispositivos.

## Publicação
O deploy foi preparado para GitHub Pages por meio do workflow localizado em `.github/workflows/deploy-pages.yml`.

A publicação final depende da criação do repositório remoto, do envio do projeto e da ativação do GitHub Pages nas configurações do repositório.
