# Classic Car Restoration Website

Website simples de uma página para oficina de restauro de carros clássicos, com galeria moderna e mapa.

## ✨ Funcionalidades

- Design limpo, responsivo e inspirado na linguagem visual da Importrust
- Galeria automática com agrupamento por carro (pasta = carro)
- Modal com visualização de imagens grandes e navegação por miniaturas
- Mapa Google Maps com localização real da oficina
- Botão “Request a Quote” fixo em várias seções

## 🗂 Estrutura de Ficheiros

project-root/
├── index.html ← Página principal
├── README.md ← Este ficheiro
└── cars/ ← Onde colocas os carros
├── car1/
│ ├── 1.jpg
│ └── ...
└── car2/
├── 1.jpg


## ➕ Como Adicionar um Carro

1. Cria uma nova pasta dentro de `cars/`, por exemplo: `car5`
2. Adiciona as imagens como `1.jpg`, `2.jpg`, ... até no máximo `10.jpg`
3. Edita o ficheiro `index.html` e adiciona o nome da nova pasta no array `const cars = [...]`

```js
const cars = [\"car1\", \"car2\", \"car5\"];

    Feito! O novo carro aparece automaticamente na galeria
