<template>
  <section>
    <div class="hero h-fit" style="background-image: url(https://daisyui.com/images/stock/photo-1507358522600-9f71e620c44e.jpg);">
      <div class="hero-overlay bg-opacity-60"></div>
        <div class="hero-content text-center py-60 text-slate-100">
          <div class="max-w-md">
            <h1 class="mb-5  w-fit fontheader">Where We're Based</h1>
            <p class="text-xl">At JM Studios we are based in Hawaii and the Pacific Northwest- which includes Washington state and Oregon.</p>
        </div>
      </div>
    </div>
  </section>
  
  <div class="flex flex-col py-10 bg-slate-100">
  <div class="flex flex-row justify-center items-center bg-gray-600 h-2"></div>
    <div class="flex flex-col p-20 text-slate-900 bg-slate-100">
    <div class="flex flex-row fontheader2 justify-center items-center">Putting Customers First</div>
      <div class="flex flex-col text-2xl justify-center items-center">
        <div>We prioritize customer service with high quality performance. We want to ensure that your</div>
        <div>experience with us from start to finish is as memorable as the video we will make for you. </div>
      </div>
  </div>
  <div class="flex flex-row justify-center items-center bg-gray-600 h-2"></div>
</div>
  <Meettheteam/>

<div class="hero min-h-48 bg-slate-100 text-slate-900">
  <div class="p-10">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <div class="text-center lg:text-left">
        <h1 class="text-5xl font-bold">Login now!</h1>
        <p class="py-6 text-lg">Login to book events, get deals, and receive updates and information from our team getting the best possible experience.</p>
      </div>
      <div class="card shrink-0 w-full max-w-sm shadow-2xl bg-base-100 text-slate-300">
        <form class="card-body bg-slate-4800 rounded-lg">
          <div class="form-control text-slate">
            <label class="label">
              <span class="label-text">Email</span>
            </label>
            <input type="email" placeholder="email" class="input input-bordered" required />
          </div>
          <div class="form-control">
            <label class="label">
              <span class="label-text">Password</span>
            </label>
            <input type="password" placeholder="password" class="input input-bordered" required />
            <label class="label">
              <a href="#" class="label-text-alt link link-hover">Forgot password?</a>
            </label>
          </div>
          <div class="form-control mt-6">
            <button class="btn btn-primary">Login</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</div>


</template>