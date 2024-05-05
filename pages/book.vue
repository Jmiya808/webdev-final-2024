<template>
  <div class="flex flex-row py-20 bg-slate-100">
    <div class="justify-center px-40 ">
      <ul class="steps steps-vertical h-full text-2xl">
        <li class="step step-primary">Personal Information</li>
        <li class="step">Choose Plan</li>
        <li class="step">Schdeule Date</li>
        <li class="step">Additional Features</li>
      </ul>
    </div>
    <div class="flex flex-col gap-20">
      <div class=" flex flex-row fontheader2 justify-center items-center text-slate-900">Fill Out The Information Below.</div>
      <section class="flex flex-col gap-4">
        <div class="text-4xl font-medium text-slate-900">Personal Information</div>
        <div class="flex flex-col pt-5 pb-10 pl-5 bg-gray-200 w-full gap-1 rounded-2xl">
          <div class="text-gray-600">What is your name?</div>
          <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs bg-slate-100" />
        </div>
        <div class="flex flex-col pt-5 pb-10 pl-5 bg-gray-200 w-full gap-1 rounded-2xl">
          <div class="text-gray-600">Phone Number</div>
          <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs bg-slate-100" />
        </div>
        <div class="flex flex-col pt-5 pb-10 pl-5 bg-gray-200 w-full gap-1 rounded-2xl">
          <div class="text-gray-600">Email</div>
          <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs bg-slate-100" />
        </div>
      </section>
      <section class="flex flex-col gap-4">
        <div class="text-4xl font-medium text-slate-900">Choose a Plan</div>
        <div class="flex flex-col pt-5 pb-10 pl-5 bg-gray-200 w-full gap-1 rounded-2xl">
          <div class="text-gray-600">Choose a Plan</div>
          <div class="dropdown">
            <div tabindex="0" role="button" class="btn m-1 bg-slate-100 hover:bg-slate-100 border-0">Choose a Plan</div>
            <ul tabindex="0" class="dropdown-content z-[1] menu p-2 shadow bg-base-100 rounded-box w-52">
              <li><a>Value Bundle</a></li>
              <li><a>Professional Bundle</a></li>
              <li><a>Elite Bundle</a></li>
            </ul>
          </div>
        </div>
      </section>
      <section class="flex flex-col gap-4">
        <div class="text-4xl font-medium text-slate-900">Book a Date</div>
        <div class="flex flex-col pt-5 pb-10 pl-5 bg-gray-200 w-full gap-1 rounded-2xl">
          <div class="text-gray-600">Book a Date.</div>
          <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs bg-slate-100" />
        </div>
        <div class="flex flex-col pt-5 pb-10 pl-5 bg-gray-200 w-full gap-1 rounded-2xl">
          <div class="text-gray-600">Select a Time.</div>
          <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs bg-slate-100"/>
        </div>
      </section>
      <section class="flex flex-col gap-4">
        <div class="text-4xl font-medium text-slate-900">Additional Services</div>
        <div class="form-control pt-5 pb-10 pl-5 pr-5 bg-gray-200 w-full gap-1 rounded-2xl text-slate-900">
          <label class="label cursor-pointer">
            <span class="label-text text-slate-600 text-xl">Drone Footage ($300 per session)</span> 
            <input type="checkbox" class="checkbox bg-slate-100" />
          </label>
          <label class="label cursor-pointer">
            <span class="label-text text-slate-600 text-xl">Additional Hours ($250 per added hour)</span> 
            <input type="checkbox"  class="checkbox bg-slate-100" />
          </label>
          <label class="label cursor-pointer">
            <span class="label-text text-slate-600 text-xl">Revisions ($75/hr with 3hr min.)</span> 
            <input type="checkbox" class="checkbox bg-slate-100" />
          </label>
          <label class="label cursor-pointer">
            <span class="label-text text-slate-600 text-xl">Wedding Film USB (32 GB Drive | $200)</span> 
            <input type="checkbox" class="checkbox bg-slate-100" />
          </label>
          <label class="label cursor-pointer">
            <span class="label-text text-slate-600 text-xl">Raw Footage ($120/hr | minimum 3 hrs)</span> 
            <input type="checkbox" class="checkbox bg-slate-100" />
          </label>
          <label class="label cursor-pointer">
            <span class="label-text text-slate-600 text-xl">Video Editing ($175/hr | min 3 hrs)</span> 
            <input type="checkbox" class="checkbox bg-slate-100" />
          </label>
          <label class="label cursor-pointer">
            <span class="label-text text-slate-600 text-xl">Events Outside Hawaii & Oregon (Travel Expenses)</span> 
            <input type="checkbox" class="checkbox bg-slate-100" />
          </label>
        </div>
      </section>
      <section class="flex flex-row justify-end ">
      <button class="btn btn-primary">Confirm Booking</button>
      </section>
    </div>
  </div>
</template>