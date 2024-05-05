<template>
<footer>
  <div  class="footer p-10 bg-slate-900 text-base-content">
    <nav>
      <h6 class="footer-title">Services</h6> 
      <a class="link link-hover">Branding</a>
      <a class="link link-hover">Design</a>
      <a class="link link-hover">Marketing</a>
      <a class="link link-hover">Advertisement</a>
    </nav> 
    <nav>
      <h6 class="footer-title">Company</h6> 
      <a class="link link-hover">About us</a>
      <a class="link link-hover">Contact</a>
      <a class="link link-hover">Jobs</a>
      <a class="link link-hover">Press kit</a>
    </nav> 
    <nav>
      <h6 class="footer-title">Legal</h6> 
      <a class="link link-hover">Terms of use</a>
      <a class="link link-hover">Privacy policy</a>
      <a class="link link-hover">Cookie policy</a>
    </nav> 
    <form>
      <h6 class="footer-title">Newsletter</h6> 
      <fieldset class="form-control w-80">
        <label class="label">
          <span class="label-text">Enter your email address</span>
        </label> 
        <div class="join">
          <input type="text" placeholder="username@site.com" class="input input-bordered join-item" /> 
          <button class="btn btn-primary join-item">Subscribe</button>
        </div>
      </fieldset>
    </form>
</div>

<!-- Copyright section-->
<section class="footer footer-center p-4 bg-base-300 text-base-content">
  <aside>
    <p>Copyright © 2024 - All right reserved by ACME Industries Ltd</p>
  </aside>
</section>

</footer>
</template>

<!-- Style Guide-->
<style scoped>
.roboto{
  font-family: Roboto, sans-serif;
}
.pic{
max-width:60px;
max-height: 60px;
}
  /* Bootstrap Styles */
  .btn-outline-light {
    color: #4F8A10;
    border-color: #4F8A10;
  }
  .btn-outline-light:hover {
    color: #fff;
    background-color: #4F8A10;
    border-color: #4F8A10;
  }
  .btn-floating {
    box-shadow: none;
  }
  /* Social Media Icons */
  .social-icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 5%; /* Adjust as needed */
    height: auto; /* Maintain aspect ratio */
    margin: 0 5px; /* Add spacing between icons */
    font-size: 28px; /* Adjust size as needed */
    color: #94A3B8; /* slate-400 color */
  }
  .social-icon:hover {
  color: #D2D6DC; /* slate-50 color */
}
  /* Add vertical spacing */
  .my-4 {
    margin-top: 1rem; /* Adjust as needed */
    margin-bottom: 1rem; /* Adjust as needed */
  }
  /* Font Awesome Styles */
  @import "~@fortawesome/fontawesome-free/css/all.css";
</style>
