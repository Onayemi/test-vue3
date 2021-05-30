<template>
  <div>
      <!-- ======= Header ======= -->
    <header id="header" class="fixed-top d-flex align-items-center">
      <div class="container d-flex align-items-center">

        <h1 class="logo me-auto"><router-link to="/">Sailor</router-link></h1>
        <nav id="navbar" class="navbar">
          <ul>
            <li><router-link to="/" class="active">Home</router-link></li>

            <li class="dropdown"><a href="#"><span>About</span> <i class="bi bi-chevron-down"></i></a>
              <ul>
                <li><router-link to="/about">About</router-link></li>
                <li><a href="team.html">Team</a></li>
                <li><a href="testimonials.html">Testimonials</a></li>

                <li class="dropdown"><a href="#"><span>Deep Drop Down</span> <i class="bi bi-chevron-right"></i></a>
                  <ul>
                    <li><a href="#">Deep Drop Down 1</a></li>
                    <li><a href="#">Deep Drop Down 2</a></li>
                  </ul>
                </li>
              </ul>
            </li>
            <li><router-link to="/services">Services</router-link></li>
            <li><a href="portfolio.html">Portfolio</a></li>
            <!-- <li><a href="pricing.html">Pricing</a></li>
            <li><a href="blog.html">Blog</a></li> -->

            <li><router-link to="/contact">Contact</router-link></li>
            <li><router-link to="/" class="getstarted">Get Started</router-link></li>
          </ul>
          <i class="bi bi-list mobile-nav-toggle"></i>
        </nav><!-- .navbar -->

      </div>
    </header><!-- End Header -->
  </div>
</template>

<script>
/*eslint-disable*/ 
export default {
  
}
</script>