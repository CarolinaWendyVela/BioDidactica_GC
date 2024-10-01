---
title: "detail-1"
layout: "../../layouts/Layout.astro"
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/img1.webp" alt="camiseta" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Cuerpo humano</h2>
   <h4>Explorando la Complejidad del Cuerpo Humano</h4>
   <p class='max-w-md'> El cuerpo humano es una máquina compleja formada por sistemas que trabajan juntos. El esqueleto, con 206 huesos, da soporte y protege órganos vitales. Los más de 600 músculos permiten el movimiento. El corazón, parte del sistema circulatorio, bombea sangre que transporta oxígeno y nutrientes. El sistema respiratorio toma oxígeno y elimina dióxido de carbono. El sistema digestivo descompone los alimentos en nutrientes, y el sistema nervioso, dirigido por el cerebro, coordina todas las funciones del cuerpo.</p>
<button class='w-20 h-7 border-gray-50 border-2 rounded-md flex justify-center items-center hover:bg-blue-900 transition'>Buy</button>

   </div>
</section>

<style>
   section{
      width:100%;
      min-height: calc(100vh - 52px)
   }

</style>
