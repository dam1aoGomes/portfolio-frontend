<template>
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
          <button class="btn btn-primary">Conheça</button>
        </div>
      </div>
    </div>
    <!---->
    <div class="mockup-browser bg-base-300 border m-5" v-if="showWebBrowse">
      <div class="mockup-browser-toolbar">
        <div class="input">https://postlab-frontend.vercel.app/</div>
      </div>
      <div class="bg-base-200 flex justify-center ">
        <img src="/public/images/postlab-web-browser.png" class="">
      </div>
    </div>
    <!---->
    <div class="mockup-phone mt-20" v-if="showWebPhone">
      <div class="camera"></div>
      <div class="display">
        <img src="/public/images/postlab-web-phone.png" class="mt-10">
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
const showWebBrowse = ref(false);
const showWebPhone  = ref(false);

function changeExample() {
  if(window.innerWidth >= 750) {
    showWebBrowse.value = true;
    showWebPhone.value = false;
  } else {
    showWebBrowse.value = false;
    showWebPhone.value = true;  
  }
}

onMounted(changeExample);
</script>
