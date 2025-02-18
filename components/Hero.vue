<template>
    <div class="hero bg-base-200 h-1/2">
        <div class="hero-content flex-col lg:flex-row">
            <img src="/images/damiao.jpg" class="w-1/2 md:w-1/5 rounded-full shadow-2xl" />
            <div>
                <h1 class="text-3xl font-bold md:ml-20">Damião Gomes</h1>
                <p class="text-md max-w-2xl mt-2 text-justify md:ml-20">
                    Desenvolvedor Full Stack com experiência em Vue, Nuxt, Tailwind, TypeScript, Node.js, Flask, FastAPI, PostGresSQL e MySQL.
                    Apaixonado por criar soluções eficientes e escaláveis.
                </p>
                <p class="text-md max-w-2xl mt-2 text-justify md:ml-20">
                    Cursando Ciência da Computação na Universidade Federal do Ceará, 
                    e com curso técnico em informática por escola profissionalizante.</p>
                <div class="flex w-1/3 md:w-1/6 md:justify-between mt-10 md:ml-20">
                    <NuxtLink to="https://www.linkedin.com/in/damiao-gomes/">
                        <img src="https://img.icons8.com/?size=100&id=13930&format=png&color=000000" class="w-1/2">
                    </NuxtLink>
                    <NuxtLink to="https://github.com/dam1aoGomes/">
                        <img src="https://img.icons8.com/?size=100&id=FVTvJkWPqGJ3&format=png&color=000000" class="w-1/2">
                    </NuxtLink>
                </div>
            </div>
        </div>
    </div>
</template>