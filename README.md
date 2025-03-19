#🍕 PizzariaHut  

Bem-vindo ao **PizzariaHut**! Um projeto moderno para gestão de pedidos e cardápio de pizzaria, desenvolvido com **Vue.js** e **Vite**. 

<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-3.3.4-42b883?style=for-the-badge&logo=vue.js&logoColor=white">
  <img src="https://img.shields.io/badge/Vite-4.4.9-blueviolet?style=for-the-badge&logo=vite&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-5.1.6-3178c6?style=for-the-badge&logo=typescript&logoColor=white">
</p>


## 🚀 Funcionalidades
- Interface moderna utilizando **Vue.Js** e **Vite**
- Pesquisar os dados
- Diversos estilos de cards Ingredientes
- Fonte estilizada via Google Fonts


![Gravando 2025-03-19 081926](https://github.com/user-attachments/assets/35359e4f-3eed-4d06-864c-77d849f0f025)


## 📂 Estrutura do Projeto
```
/
├── .gitignore
├── .vscode
    └── extensions.json
├── README.md
├── env.d.ts
├── index.html
├── package-lock.json
├── package.json
├── public
    ├── favicon.ico
    └── imagens
    │   ├── icones
    │       └── categorias_ingredientes
    │       │   ├── acucares_e_adocantes.png
    │       │   ├── doces_e_guloseimas.png
    │       │   ├── farinhas_e_fermentos.png
    │       │   ├── frutas_frescas.png
    │       │   ├── frutas_secas.png
    │       │   ├── graos_cerais_e_leguminosas.png
    │       │   ├── hortalicas_e_verduras.png
    │       │   ├── laticinios_e_ovos.png
    │       │   ├── oleos_gorduras_e_vinagres.png
    │       │   ├── paes_e_massas.png
    │       │   ├── proteinas_animais.png
    │       │   └── temperos_e_especiarias.png
    │   └── receitas
    │       ├── alho_assado.png
    │       ├── arroz_de_alho.png
    │       ├── bacalhau_com_chips_de_alho.png
    │       ├── creme_de_galinha.png
    │       ├── macarrao_de_alho_e_oleo.png
    │       ├── manteiga_com_tomilho_e_alho.png
    │       ├── milkshake_de_chocolate.png
    │       ├── mousse_de_chocolate.png
    │       ├── panqueca.png
    │       ├── pao_de_alho.png
    │       ├── pasta_de_alho_assado.png
    │       ├── pate_de_alho_assado.png
    │       └── tortei.png
├── src
    ├── App.vue
    ├── assets
    │   ├── imagens
    │   │   ├── Pizzaria.svg
    │   │   ├── fundo-banner.png
    │   │   ├── icones
    │   │   │   └── lista-vazia.svg
    │   │   ├── iconpizza.png
    │   │   ├── logo.svg
    │   │   ├── pesquisa.svg
    │   │   └── pizzaria.png
    │   └── main.css
    ├── components
    │   ├── Banner.vue
    │   ├── BotaoPrincipal.vue
    │   ├── CardCategoria.vue
    │   ├── CardReceita.vue
    │   ├── ConteudoPrincipal.vue
    │   ├── IngredienteSelecionavel.vue
    │   ├── MostrarReceitas.vue
    │   ├── Rodape.vue
    │   ├── SelecionarIngredientes.vue
    │   ├── SuaLista.vue
    │   └── Tag.vue
    ├── http
    │   └── index.ts
    ├── interfaces
    │   ├── ICategoria.ts
    │   └── IReceita.ts
    ├── main.ts
    └── operacoes
    │   └── listas.ts
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## 🎨 Tecnologias Utilizadas
- Vue.JS
- Vite
- CSS
- Tyescript

## 🔧 Como Executar
1. Clone este repositório:
   ```sh
   git clone https://github.com/MatheusForstner/pizzariahut.git
   ```
2. Abra o comando no [localhost](http://localhost:5173/) `npm run dev` em seu navegador preferido.

## 📌 Sobre o Projeto

O **PizzariaHut** foi desenvolvido para otimizar a gestão de pedidos em uma pizzaria, proporcionando uma experiência rápida e eficiente para clientes e atendentes.  

Com este sistema, é possível:  
✅ Visualizar o cardápio com preços e descrições detalhadas  
✅ Adicionar itens ao carrinho de forma intuitiva  
✅ Finalizar pedidos de maneira prática  
✅ Gerenciar produtos e categorias no painel administrativo  

Nosso objetivo é facilitar o atendimento e tornar a experiência do usuário mais agradável! 🎯  

## 📝 Licença
Este projeto é de uso livre para estudos e aprimoramento pessoal.

---
**Desenvolvido por [Matheus Forstner](https://github.com/MatheusForstner)**
