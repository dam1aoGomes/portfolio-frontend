<template>
  <NavBar />
  <!--Hero-->
  <div class="flex flex-col items-center">
    <div class="hero bg-base-200 min-h-screen">
      <div class="hero-content text-center">
        <div class="max-w-md">
          <h1 class="text-5xl font-bold">PostLab</h1>
          <p class="py-6 text-justify">
            O PostLab é uma plataforma dinâmica de postagens que permite compartilhar ideias, artigos e projetos de
            forma
            intuitiva e organizada.
            Desenvolvido com tecnologia moderna, o site oferece uma interface minimalista e responsiva,
            garantindo uma experiência fluida tanto para escritores quanto para leitores.
          </p>
          <NuxtLink to="https://github.com/dam1aoGomes/postlab-frontend">
            <button class="btn btn-neutral m-1">GitHub Front-End</button>
          </NuxtLink>
          <NuxtLink to="https://github.com/dam1aoGomes/postlab-backend">
            <button class="btn btn-neutral m-1">GitHub Back-End</button>
          </NuxtLink>
        </div>
      </div>
    </div>
    <!--Ideia-->
    <div class="hero bg-base-200 min-h-screen">
      <div class="hero-content text-center">
        <div class="max-w-md">
          <h1 class="text-5xl font-bold">Ideia</h1>
          <p class="py-6 text-justify">
            Desde que comecei meus estudos em 2019, sempre tive o desejo de criar um site de postagens simples, mas
            funcional. Com as ferramentas que eu conhecia na época — PHP, MySQL, HTML, CSS e JavaScript — desenvolvi
            diversos sites, porém todos eram bastante amadores.
            Naquele tempo, eu ainda não dominava autenticação de usuários nem paginação de posts, o que limitava
            bastante os projetos.
            Agora, decidi revisitar essa ideia e criar este projeto como uma homenagem ao meu eu do passado, mostrando o
            quanto evoluí ao longo dos anos, mas sem perder a essência inicial.
          </p>
          <p class="py-6 text-justify">
            O <b>PostLab</b> é mais do que um simples site de postagens: é o primeiro marco do meu portfólio e uma prova
            do meu crescimento como desenvolvedor.
          </p>
        </div>
      </div>
    </div>
    <!--Tecnologias-->
    <div class="w-full h-screen flex flex-col items-center">
      <h1 class="text-5xl font-bold mt-10">Tecnologias</h1>
      <div class="w-full flex flex-wrap items-center justify-center md:items-start md:justify-start">
        <PostlabCards />
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>
