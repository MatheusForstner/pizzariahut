<template>
    <header class="banner">
      <div class="apresentacao">
        <img src="../assets/imagens/Pizzaria.svg" alt="Logo de Cookin' Up" class="logo">
      
        <p class="cabecalho-lg frase-cabecalho">
          <span class="texto-verde">Um banquete de ideias para despertar  o chefe que há em você!</span>
        </p>
  
        <p class="subtitulo-lg">
          Explore novas receitas todos os dias com os ingredientes que estão ao seu alcance!
        </p>
      </div>
  
      <img src="../assets/imagens/pizzaria.png" alt="" class="foto-banner">
    </header>
  </template>

<style scoped>
.banner {
padding: 4rem 7.5rem;
color: var(--creme);

display: flex;
justify-content: space-between;
align-items: center;
column-gap: 3.25rem;
}

.foto-banner {
  position: relative;
  width: 160px;
  aspect-ratio: 1;
  border-radius: 50%;
  outline: 30px solid rgba(0, 0, 0, 0.35);
  outline-offset: -12px;
}

.foto-banner img {
  display: block;
  width: 100%;
  aspect-ratio: 1;
  object-fit: cover;
  object-position: top;
  border-radius: inherit;
}


.logo {
height: 4.5rem;
margin-bottom: 3rem;
}

.frase-cabecalho {
margin-bottom: 2rem;
}

.texto-verde {
color: var(--preto, #000);
}

.foto-banner {
width: 35rem;
}

@media only screen and (max-width: 1300px) {
.banner {
  padding: 4rem 3.75rem;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
}

.logo {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
}

@media only screen and (max-width: 767px) {
.banner {
  padding: 4rem 1.5rem;
}

.foto-banner {
  width: min(100%, 21.25rem);
}
}
</style>