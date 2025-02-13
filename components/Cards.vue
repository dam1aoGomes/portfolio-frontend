<template>
  <div class="flex items-start">
    <!--Card PostLab-->
    <div class="card bg-base-100 image-full w-96 shadow-xl m-5 p-5">
      <figure>
        <img src="/public/images/postlab-card2.png" alt="PostLab" class="w-full" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">PostLab</h2>
        <p>O PostLab é uma plataforma dinâmica de postagens que permite compartilhar ideias, artigos e projetos de forma
          intuitiva e organizada.</p>
        <div class="card-actions justify-start mb-10">
          <img src="/public/favicon.ico" class="size-7">
          <img src="https://icon.icepanel.io/Technology/svg/Tailwind-CSS.svg" class="size-7">
          <img src="https://icon.icepanel.io/Technology/svg/FastAPI.svg" class="size-7">
          <img src="https://icon.icepanel.io/Technology/svg/PostgresSQL.svg" class="size-7">
        </div>
        <div class="card-actions justify-end">
          <NuxtLink to="https://postlab-frontend.vercel.app/" target="_blank"><button class="btn">Visite o site</button></NuxtLink>
          <NuxtLink to="/project/postlab"><button class="btn btn-primary">Conheça mais</button></NuxtLink>
        </div>
      </div>
    </div>
    <!---->
  </div>
</template>
