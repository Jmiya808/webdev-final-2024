<template>
<div class="flex flex-col bg-slate-100 p-20">
  <div class="flex flex-1 fontheader text-slate-800 items-center justify-center">Meet the Team</div>
  <div class="flex flex-row justify-center gap-10 py-10">
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure><img class="" src="public/Fern.png" alt="Shoes" /></figure>
      <div class="card-body h-60">
        <h2 class="card-title text-slate-100">Fernando Lopez</h2>
        <p class="text-slate-100">Freelance Cinematographer based in Washington, bringing experience in music videos and short films</p>
        <div class="flex flex-row card-actions justify-between items-center">
          <div>Based in Washington</div>
          <button class="btn btn-primary">Learn More</button>
        </div>
      </div>
    </div>
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure><img src="public/Milan.jpeg" alt="Shoes" /></figure>
      <div class="card-body">
        <h2 class="card-title text-slate-100">Milan Araujo</h2>
        <p class="text-slate-100">Freelance cinematographer and photographer based in Oregon, bringing expereince in wedding, music video cinematography and photography.</p>
        <div class="flex flex-row card-actions justify-between items-center">
          <div>Based in Oregon</div>
          <button class="btn btn-primary">Learn More</button>
        </div>
      </div>
    </div>
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure><img src="public/Ken.jpeg" alt="Shoes" /></figure>
      <div class="card-body">
        <h2 class="card-title text-slate-100">Ken Ogihara</h2>
        <p class="text-slate-100">Freelance cinematographer and photographer based in Hawaii and California, bringin experience in wedding cinematographer and graduation photography.</p>
        <div class="flex flex-row card-actions justify-between items-center">
          <div>Based in Hawaii/California</div>
          <button class="btn btn-primary">Learn More</button>
        </div>
      </div>
    </div>
   
  </div>
</div>
</template>

<style>
.fontheader1{
font-size: 75px;
font-weight: 700;
justify-content: center;
align-items: center;
}

.fontheader2{
font-size: 55px;
font-weight: 700;
justify-content: center;
align-items: center;
}

.fontbody{
font-size: 20px;
font-weight: 400;
justify-content: center;
align-items: center;
}
</style>