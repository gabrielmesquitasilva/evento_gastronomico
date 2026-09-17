Portal de Eventos – Universidade Vale do Rio (Gastronomia)

Projeto acadêmico da disciplina de Tecnologias Web: um site front-end para
divulgação de eventos acadêmicos da área de Gastronomia (palestras,
minicursos, workshops e oficinas), desenvolvido com **HTML semântico** e
**CSS puro**, sem uso de JavaScript ou frameworks.

Site publicado
> `https://gabrielmesquitasilva.github.io/evento_gastronomico/index.html`

Páginas

- **`index.html`** – Home: apresentação da universidade e cards com os 6
  eventos disponíveis (imagem, categoria, data, horário, local e descrição),
  organizados em Flexbox.
- **`programacao.html`** – Programação geral dos eventos em formato de
  tabela, com uso de `rowspan` (agrupando horários do mesmo dia) e `colspan`
  (unindo as colunas de Data e Horário no cabeçalho).
- **`inscricao.html`** – Formulário de inscrição em evento, com campos de
  nome, e-mail, curso, período, evento desejado, modalidade
  (presencial/online) e confirmação.

Tecnologias utilizadas

- HTML5 semântico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3 (Flexbox, Media Queries, seletores de classe/elemento, transições,
  sombras e bordas arredondadas)
- Sem JavaScript, Bootstrap, Tailwind ou qualquer outro framework

Estrutura do projeto

```
evento_gastronomia/
├── index.html
├── programacao.html
├── inscricao.html
├── css/
│   └── style.css
├── img/
│   ├── gastro-sustentavel.webp
│   ├── mini-panificacao.jpg
│   ├── confeitaria.jfif
│   ├── vegana.jpg
│   ├── mercado.jfif
│   └── vinho.jfif
└── README.md
```
