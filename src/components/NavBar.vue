<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <RouterLink to="/">
     <img class="img-fluid " src="https://drive.google.com/file/d/189VV73Wbv_tOr1NOcJdZMR0WeR0AQFqI/view?usp=drive_link" alt="logo" loading="lazy">
    </RouterLink>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <RouterLink to="/" class="nav-link active">
           Home
          </RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link active" to="/about">
            About
          </RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link active" to="/resume">
            Resume
          </RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link active" to="/project">
            Projects
          </RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link active" to="/testimonials">
            Testimonials
          </RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link active" to="/contact">
            Contacts
          </RouterLink>
        </li>
       
      </ul>
      
    </div>
  </div>
</nav>
</template>

<script>
    export default {
        name : 'NavBarComp'
    }  
    
    
</script>

<style scoped>

</style>