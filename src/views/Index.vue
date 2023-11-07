<template>
  <!-- Header Area wrapper Starts -->
  <header id="header-wrap" class="relative">
    <!-- Navbar Start -->
    <div class="navigation w-full z-30 duration-300">
      <div class="container">
        <nav class="navbar py-2 navbar-expand-lg flex justify-between items-center relative duration-300">
          <a class="navbar-brand" href="/">
            <img src="/cad.svg" alt="Logo">
          </a>

          <div class="lg:flex lg:justify-center lg:items-center">
            <!-- LG Navigation Menu (Visible on Large Devices) -->
            <div class="lg:flex lg:items-center hidden text-green-600" id="lgNav">
              <ul class="lg:flex">
                <li class="lg:mr-5">
                  <a class="page-scroll" href="#hero-area">Home</a>
                </li>
                <li class="lg:mr-5">
                  <a class="page-scroll" href="#about">About</a>
                </li>
                <li>
                  <a class="page-scroll" href="#openings">Job Openings</a>
                </li>
              </ul>
            </div>

          </div>


          <div class="header-btn hidden sm:block sm:absolute sm:right-0 sm:mr-16 lg:static lg:mr-0">
            <a class="text-green-600 border border-green-600 px-10 py-3 rounded-full duration-300 hover:bg-green-600 hover:text-white"
              target="_blank" href="https://forms.gle/povMpsRdsJNWqLGE8">Apply</a>
          </div>
        </nav>
      </div>
    </div>
    <!-- Navbar End -->
  </header>
  <!-- Header Area wrapper End -->

  <!-- Hero Area Start -->
  <section id="hero-area" class="bg-green-100 pt-48 pb-10">
    <div class="container">
      <div class="flex justify-between">
        <div class="w-full text-center">
          <h2 class="text-4xl font-bold leading-snug text-gray-700 mb-10 wow fadeInUp" data-wow-delay="1s">Canadian Fruit
            and Produce Company</h2>
          <p class="-mt-6 text-2xl leading-snug">Fresh Produce Everyday</p> <br />
          <div class="text-center mb-10 wow fadeInUp" data-wow-delay="1.2s">
            <p class="mb-8 text-3xl leading-snug">Application is open. Click on the link below to apply</p> <br />
            <a href="https://forms.gle/povMpsRdsJNWqLGE8" target="_blank" rel="nofollow"
              class="btn bg-green-600 hover:bg-green-500">Apply Now</a>
          </div>
          <div class="text-center wow fadeInUp" data-wow-delay="1.6s">
            <img class="img-fluid mx-auto" src="/Watermelon.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Hero Area End -->

  <!-- About Section Start -->
  <section id="about" class="py-24">
    <div class="container">
      <div class="text-center">
        <h2 class="mb-12 section-heading wow fadeInDown" data-wow-delay="0.3s">About Us</h2>
      </div>
      <div class="flex flex-wrap">
        <!-- Services item -->
        <div class="w-full sm:w-1/2 md:w-1/2 lg:w-full text-center ">
          <div class="m-4 wow fadeInRight" data-wow-delay="0.3s">

            <div>
              <h3 class="service-title">Who We Are</h3>
              <p class="text-gray-600">Canadian Fruit and Produce Company is a distributor and supplier based in Toronto,
                Ontario. We provide our clients with the best quality products at an exceptionally low price and supply
                them with services, including Product Sourcing and Deliveries. Since 1925, we have played an important
                role in providing our community with fresh produce all year round. Want to learn more? Contact us today.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- About Section End -->

  <!-- Job Openings -->
  <section id="openings" class="mb-20">
    <div class="container">
      <div class="text-center">
        <h2 class="mb-12 section-heading wow fadeInDown" data-wow-delay="0.3s">Job Openings</h2>
      </div>
      <div class="flex flex-wrap">
        <!-- Services item -->
        <div class="w-full sm:w-1/2 md:w-1/2 lg:w-1/3">
          <div class="m-4 wow fadeInRight" data-wow-delay="0.3s">
            <div class="icon text-5xl">
              <i class="lni lni-cog"></i>
            </div>
            <div>
              <h3 class="service-title">harvesting labourer</h3>
              <p class="text-gray-600">Labourers assist with various aspects of crop harvesting, including planting, tending to crops, and gathering produce. Their duties can be diverse and may change with the seasons.</p>
            </div>
          </div>
        </div>
        <!-- Services item -->
        <div class="w-full sm:w-1/2 md:w-1/2 lg:w-1/3">
          <div class="m-4 wow fadeInRight" data-wow-delay="0.6s">
            <div class="icon text-5xl">
              <i class="lni lni-bar-chart"></i>
            </div>
            <div>
              <h3 class="service-title">Assistant Category Manager</h3>
              <p class="text-gray-600">Responsible for supporting the Category Manager in various aspects of category management within a retail, e-commerce, or supply chain environment. </p>
            </div>
          </div>
        </div>
        <!-- Services item -->
        <div class="w-full sm:w-1/2 md:w-1/2 lg:w-1/3">
          <div class="m-4 wow fadeInRight" data-wow-delay="0.9s">
            <div class="icon text-5xl">
              <i class="lni lni-briefcase"></i>
            </div>
            <div>
              <h3 class="service-title">Consumer Insights Analyst</h3>
              <p class="text-gray-600">Help make informed decisions and develop effective marketing, product development, and customer engagement strategies.</p>
            </div>
          </div>
        </div>
        <!-- Services item -->
        <div class="w-full sm:w-1/2 md:w-1/2 lg:w-1/3">
          <div class="m-4 wow fadeInRight" data-wow-delay="1.2s">
            <div class="icon text-5xl">
              <i class="lni lni-pencil-alt"></i>
            </div>
            <div>
              <h3 class="service-title">Quality Assurance Supervisor</h3>
              <p class="text-gray-600">Oversee the quality control processes and procedures to ensure that products or services meet predetermined quality standards and specifications.</p>
            </div>
          </div>
        </div>
        <!-- Services item -->
        <div class="w-full sm:w-1/2 md:w-1/2 lg:w-1/3">
          <div class="m-4 wow fadeInRight" data-wow-delay="1.5s">
            <div class="icon text-5xl">
              <i class="lni lni-layers"></i>
            </div>
            <div>
              <h3 class="service-title">OH&S and Food Safety Coordinator</h3>
              <p class="text-gray-600">Ensure the organization complies with all relevant safety regulations and standards to create a safe working environment.</p>
            </div>
          </div>
        </div>
        <!-- Services item -->
        <div class="w-full sm:w-1/2 md:w-1/2 lg:w-1/3">
          <div class="m-4 wow fadeInRight" data-wow-delay="1.8s">
            <div class="icon text-5xl">
              <i class="lni lni-layers"></i>
            </div>
            <div>
              <h3 class="service-title">National Account Manager</h3>
              <p class="text-gray-600">Develop and maintain strong, long-term relationships with national or regional accounts, understanding their needs and objectives.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Job Openings End -->


  <!-- Map Section Start -->
  <section id="google-map-area">
    <div class="mx-6 mb-6">
      <div class="flex">
        <div class="w-full">
          <object style="border:0; height: 450px; width: 100%;"
            data="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2887.926533741434!2d-79.4846256!3d43.628887999999996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x882b3613195d050d%3A0x792a585aa5cdf392!2s165%20The%20Queensway%2C%20Etobicoke%2C%20ON%20M8Y%201H8%2C%20Canada!5e0!3m2!1sen!2suk!4v1699358868340!5m2!1sen!2suk"></object>

        </div>
      </div>
    </div>
  </section>
  <!-- Map Section End -->



  <section class="bg-gray-800 py-6 border-t-2 border-gray-700 border-dotted">
    <div class="container">
      <div class="flex flex-wrap">
        <div class="w-full text-center">
          <p class="text-white">416-259-5007</p>

          <p class="text-white">©2020 by Canadian Fruit and Produce Company.</p>
        </div>
      </div>
    </div>
  </section>

<!-- Go to Top Link -->
<a href="#"
  class="back-to-top w-10 h-10 fixed bottom-0 right-0 mb-5 mr-5 flex items-center justify-center rounded-full bg-green-600 text-white text-lg z-20 duration-300 hover:bg-green-400">
  <i class="lni lni-arrow-up"></i>
</a></template>