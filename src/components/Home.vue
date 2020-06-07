<template>
  <div>
      <header>
          <div class="md:flex items-center justify-around top-navbar text-sm bg-secondary text-white text-center">
                <div class="py-2 flex items-center justify-center">
                    <svg aria-hidden="true" data-prefix="fas" data-icon="clock" 
                    class="h-5 w-5 svg-inline--fa fa-clock fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm92.49 313l-20 25a16 16 0 01-22.49 2.5l-67-49.72a40 40 0 01-15-31.23V112a16 16 0 0116-16h32a16 16 0 0116 16v144l58 42.5a16 16 0 012.49 22.5z"/></svg>
                    <h1 class="mx-2">Opening Hours: Mon-Fri 6.00am - 18.00pm</h1>
                </div>
                <div class="">
                 <h2 class="py-2">Sunday Closed</h2> 
                </div>
                <div>
                    <ul class="flex justify-around text-sm py-5">
                        <li class="px-5"><a href="">FAQ</a></li>
                        <li class="border-r-2 border-l-2 px-5"><a href="">Help Desk</a></li>
                        <li class="px-5"><a href="">Support</a></li>
                    </ul>
                </div>

          </div>

          <div class="social bg-gray-100 md:flex justify-around items-center">
              <div class="brand flex justify-center p-5 items-center">
                  <div class="bg-secondary rounded-full p-5 bg-logo bg-cover ">
                      <svg aria-hidden="true" data-prefix="fas" 
                      data-icon="microscope" 
                      class="text-white h-12 w-12 svg-inline--fa fa-microscope fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M160 320h12v16c0 8.84 7.16 16 16 16h40c8.84 0 16-7.16 16-16v-16h12c17.67 0 32-14.33 32-32V64c0-17.67-14.33-32-32-32V16c0-8.84-7.16-16-16-16h-64c-8.84 0-16 7.16-16 16v16c-17.67 0-32 14.33-32 32v224c0 17.67 14.33 32 32 32zm304 128h-1.29C493.24 413.99 512 369.2 512 320c0-105.88-86.12-192-192-192v64c70.58 0 128 57.42 128 128s-57.42 128-128 128H48c-26.51 0-48 21.49-48 48 0 8.84 7.16 16 16 16h480c8.84 0 16-7.16 16-16 0-26.51-21.49-48-48-48zm-360-32h208c4.42 0 8-3.58 8-8v-16c0-4.42-3.58-8-8-8H104c-4.42 0-8 3.58-8 8v16c0 4.42 3.58 8 8 8z"/></svg>
                  </div>
                  <div class="ml-2">
                      <h2 class="font-montserrat"><a href="/"> LAB CM</a>    </h2>
                      <span class="text-xs text-gray-500">Lab. Analisis Clinicos</span>
                  </div>
              </div>

              <div class="text-center text-sm py-2 md:flex items-center">
                  <svg aria-hidden="true" data-prefix="fas" data-icon="envelope" 
                    class="text-secondary mx-auto h-8 w-8 svg-inline--fa fa-envelope fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M502.3 190.8c3.9-3.1 9.7-.2 9.7 4.7V400c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V195.6c0-5 5.7-7.8 9.7-4.7 22.4 17.4 52.1 39.5 154.1 113.6 21.1 15.4 56.7 47.8 92.2 47.6 35.7.3 72-32.8 92.3-47.6 102-74.1 131.6-96.3 154-113.7zM256 320c23.2.4 56.6-29.2 73.4-41.4 132.7-96.3 142.8-104.7 173.4-128.7 5.8-4.5 9.2-11.5 9.2-18.9v-19c0-26.5-21.5-48-48-48H48C21.5 64 0 85.5 0 112v19c0 7.4 3.4 14.3 9.2 18.9 30.6 23.9 40.7 32.4 173.4 128.7 16.8 12.2 50.2 41.8 73.4 41.4z"/></svg>
                    <div class="md:text-left md:px-2">
                        <p class="text-gray-500 uppercase">Mail us today</p>
                        <p class="font-semibold"><a href=""> info@domain.com</a></p>

                    </div>
              </div>

              <div class="text-center text-sm py-2 md:flex items-center">
                  <svg aria-hidden="true" 
                  data-prefix="fas" data-icon="phone" 
                  class="text-secondary mx-auto h-8 w-8 svg-inline--fa fa-phone fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M493.4 24.6l-104-24c-11.3-2.6-22.9 3.3-27.5 13.9l-48 112c-4.2 9.8-1.4 21.3 6.9 28l60.6 49.6c-36 76.7-98.9 140.5-177.2 177.2l-49.6-60.6c-6.8-8.3-18.2-11.1-28-6.9l-112 48C3.9 366.5-2 378.1.6 389.4l24 104C27.1 504.2 36.7 512 48 512c256.1 0 464-207.5 464-464 0-11.2-7.7-20.9-18.6-23.4z"/></svg>
                    <div class="md:text-left md:px-2">
                    <p class="text-gray-500 uppercase">Call us</p>
                    <p class="font-semibold">+54 9 (3735) 454545</p>
                    </div>
              </div>

              <div class="text-center text-sm py-2 md:flex items-center">
                  <svg aria-hidden="true" data-prefix="fas" 
                  data-icon="map-marker-alt" 
                  class="text-secondary mx-auto h-8 w-8 svg-inline--fa fa-map-marker-alt fa-w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><path fill="currentColor" d="M172.268 501.67C26.97 291.031 0 269.413 0 192 0 85.961 85.961 0 192 0s192 85.961 192 192c0 77.413-26.97 99.031-172.268 309.67-9.535 13.774-29.93 13.773-39.464 0zM192 272c44.183 0 80-35.817 80-80s-35.817-80-80-80-80 35.817-80 80 35.817 80 80 80z"/></svg>
                    <div class="md:text-left md:px-2">
                    <p class="text-gray-500 uppercase">Find Us</p>
                    <p class="font-semibold">25 de May. 345</p>
                    </div>
              </div>
          </div>

          <nav class="bg-gray-100 md:bg-white">
              <div class=" block md:hidden">
                  <div class="bg-secondary text-white flex justify-between p-5 items-center">
                      <span>Menu</span>
                      <button @click="shown=!shown">
                          <svg aria-hidden="true" 
                            data-prefix="fas" data-icon="bars" 
                            class="h5 w-5 svg-inline--fa fa-bars fa-w-14" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="currentColor" d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"/></svg></button>
                  </div>
              </div>
              <ul :class="[shown ? 'block' :'hidden']" class="text-gray-500 px-5 md:flex text-sm lg:text-lg mb-5 justify-around md:py-5 md:text-center transition duration-700 ease-in-out">
                  <li class="hover:bg-secondary hover:text-white  md:w-3/12 border-b border-gray-500 px-2 py-2 "><a href="" class="">Home</a></li>
                  <li class="hover:bg-secondary hover:text-white  md:w-3/12 border-b border-gray-500 bg-gray-100 md:bg-white md:border-none px-2 py-2 "><a href="" class="">Services</a></li>
                  <li class="hover:bg-secondary hover:text-white  md:w-3/12 border-b border-gray-500 bg-gray-100 md:bg-white md:border-none px-2 py-2 "><a href="" class="">About</a></li>
                  <li class="hover:bg-secondary hover:text-white  md:w-3/12 border-b border-gray-500 bg-gray-100 md:bg-white md:border-none px-2 py-2 "><a href="" class="">Contact</a></li>
              </ul>


          </nav>
      </header>
      <main>
          <!-- hero  -->
          <section class="hero bg-no-repeat bg-cover h-64 md:h-screen">
              <div class="p-5 md:p-20">
                  <h1 class="text-3xl  text-secondary  md:text-5xl capitalize font-rubik">We provide <br> <span class="text-orange-500">profesional services</span> </h1>
                  <p class="hidden md:block text-xl ">Lorem ipsum dolor sit amet consectetur, adipisicing elit. <br> Suscipit, rem! Sapiente quibusdam quam voluptas exercitationem commodi pariatur ipsam eaque saepe quia.</p>
                  <button class="font-montserrat mt-2 text-sm hover:bg-orange-500 hover:text-secondary uppercase font-semibold md:text-xl  py-2 md:my-10 md:py-5 px-5 bg-secondary text-white">Contact</button>
              </div>
          </section>
        <!-- /hero  -->

        <!-- Services  -->
            <section class="servicios mt-5 font-montserrat text-center">
                <h1 class="text-center text-gray-600 font-montserrat text-2xl">Our Servcices</h1>
                <div class="md:flex p-5">
                    <div class="text-secondary my-5 md:mx-5 w-full p-5 bg-white rounded-none ">
                        <svg aria-hidden="true" data-prefix="fas" data-icon="viruses" 
                            class="mx-auto text-orange-500 h-10 w-10 svg-inline--fa fa-viruses fa-w-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512"><path fill="currentColor" d="M624 352h-12.12c-28.51 0-42.79-34.47-22.63-54.63l8.58-8.57a16 16 0 10-22.63-22.63l-8.57 8.58c-20.16 20.16-54.63 5.88-54.63-22.63V240a16 16 0 00-32 0v12.12c0 28.51-34.47 42.79-54.63 22.63l-8.57-8.58a16 16 0 00-22.63 22.63l8.58 8.57c20.16 20.16 5.88 54.63-22.63 54.63H368a16 16 0 000 32h12.12c28.51 0 42.79 34.47 22.63 54.63l-8.58 8.57a16 16 0 1022.63 22.63l8.57-8.58c20.16-20.16 54.63-5.88 54.63 22.63V496a16 16 0 0032 0v-12.12c0-28.51 34.47-42.79 54.63-22.63l8.57 8.58a16 16 0 1022.63-22.63l-8.58-8.57c-20.16-20.16-5.88-54.63 22.63-54.63H624a16 16 0 000-32zm-144 32a32 32 0 1132-32 32 32 0 01-32 32zM346.51 213.33h16.16a21.33 21.33 0 000-42.66h-16.16c-38 0-57.05-46-30.17-72.84l11.43-11.44a21.33 21.33 0 00-30.17-30.16l-11.43 11.43c-26.88 26.88-72.84 7.85-72.84-30.17V21.33a21.33 21.33 0 00-42.66 0v16.16c0 38-46 57.05-72.84 30.17L86.4 56.23a21.33 21.33 0 00-30.17 30.16l11.43 11.44c26.88 26.88 7.85 72.84-30.17 72.84H21.33a21.33 21.33 0 000 42.66h16.16c38 0 57.05 46 30.17 72.84L56.23 297.6a21.33 21.33 0 1030.17 30.17l11.43-11.43c26.88-26.88 72.84-7.85 72.84 30.17v16.16a21.33 21.33 0 0042.66 0v-16.16c0-38 46-57.05 72.84-30.17l11.43 11.43a21.33 21.33 0 0030.17-30.17l-11.43-11.43c-26.88-26.88-7.85-72.84 30.17-72.84zM160 192a32 32 0 1132-32 32 32 0 01-32 32zm80 32a16 16 0 1116-16 16 16 0 01-16 16z"/></svg>
                        <h1 class="my-5 text-2xl font-bold ">Bacteriologia</h1>
                        <p class="md:p-5 text-gray-600 font-sans   ">Se define como la ciencia que estudia las bacterias, en el área bacteriológica de Laboratorios AC desarrollamos las técnicas de diagnóstico directo e indirecto de las infecciones ocasionadas por bacterias y también por hongos.</p>
                    </div>

                    <div class="text-secondary my-5 md:mx-5 w-full p-5 bg-white rounded-none ">
                        <svg aria-hidden="true" data-prefix="fas" data-icon="notes-medical" 
                            class="mx-auto text-orange-500 h-10 w-10 svg-inline--fa fa-notes-medical fa-w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><path fill="currentColor" d="M336 64h-80c0-35.3-28.7-64-64-64s-64 28.7-64 64H48C21.5 64 0 85.5 0 112v352c0 26.5 21.5 48 48 48h288c26.5 0 48-21.5 48-48V112c0-26.5-21.5-48-48-48zM192 40c13.3 0 24 10.7 24 24s-10.7 24-24 24-24-10.7-24-24 10.7-24 24-24zm96 304c0 4.4-3.6 8-8 8h-56v56c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8v-56h-56c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h56v-56c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v56h56c4.4 0 8 3.6 8 8v48zm0-192c0 4.4-3.6 8-8 8H104c-4.4 0-8-3.6-8-8v-16c0-4.4 3.6-8 8-8h176c4.4 0 8 3.6 8 8v16z"/></svg>
                        <h1 class="my-5 text-2xl font-bold ">Bioq. Clinica</h1>
                        <p class="md:p-5 text-gray-600 font-sans   ">La bioquímica clínica es la rama del laboratorio en la que se usan métodos químicos y bioquímicos para el estudio de las enfermedades. En la práctica, está usualmente dedicada a los estudios de la sangre, orina y otros fluidos biológicos …</p>
                    </div>

                    <div class="text-secondary my-5 md:mx-5 w-full p-5 bg-white rounded-none ">
                        <svg aria-hidden="true" data-prefix="fas" 
                        data-icon="biohazard" class="mx-auto text-orange-500 h-10 w-10svg-inline--fa fa-biohazard fa-w-18" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512"><path fill="currentColor" d="M287.9 112c18.6 0 36.2 3.8 52.8 9.6 13.3-10.3 23.6-24.3 29.5-40.7-25.2-10.9-53-17-82.2-17-29.1 0-56.9 6-82.1 16.9 5.9 16.4 16.2 30.4 29.5 40.7 16.5-5.7 34-9.5 52.5-9.5zM163.6 438.7c12-11.8 20.4-26.4 24.5-42.4-32.9-26.4-54.8-65.3-58.9-109.6-8.5-2.8-17.2-4.6-26.4-4.6-7.6 0-15.2 1-22.5 3.1 4.1 62.8 35.8 118 83.3 153.5zm224.2-42.6c4.1 16 12.5 30.7 24.5 42.5 47.4-35.5 79.1-90.7 83-153.5-7.2-2-14.7-3-22.2-3-9.2 0-18 1.9-26.6 4.7-4.1 44.2-26 82.9-58.7 109.3zm113.5-205c-17.6-10.4-36.3-16.6-55.3-19.9 6-17.7 10-36.4 10-56.2 0-41-14.5-80.8-41-112.2-2.5-3-6.6-3.7-10-1.8-3.3 1.9-4.8 6-3.6 9.7 4.5 13.8 6.6 26.3 6.6 38.5 0 67.8-53.8 122.9-120 122.9S168 117 168 49.2c0-12.1 2.2-24.7 6.6-38.5 1.2-3.7-.3-7.8-3.6-9.7-3.4-1.9-7.5-1.2-10 1.8C134.6 34.2 120 74 120 115c0 19.8 3.9 38.5 10 56.2-18.9 3.3-37.7 9.5-55.3 19.9-34.6 20.5-61 53.3-74.3 92.4-1.3 3.7.2 7.7 3.5 9.8 3.3 2 7.5 1.3 10-1.6 9.4-10.8 19-19.1 29.2-25.1 57.3-33.9 130.8-13.7 163.9 45 33.1 58.7 13.4 134-43.9 167.9-10.2 6.1-22 10.4-35.8 13.4-3.7.8-6.4 4.2-6.4 8.1.1 4 2.7 7.3 6.5 8 39.7 7.8 80.6.8 115.2-19.7 18-10.6 32.9-24.5 45.3-40.1 12.4 15.6 27.3 29.5 45.3 40.1 34.6 20.5 75.5 27.5 115.2 19.7 3.8-.7 6.4-4 6.5-8 0-3.9-2.6-7.3-6.4-8.1-13.9-2.9-25.6-7.3-35.8-13.4-57.3-33.9-77-109.2-43.9-167.9s106.6-78.9 163.9-45c10.2 6.1 19.8 14.3 29.2 25.1 2.5 2.9 6.7 3.6 10 1.6s4.8-6.1 3.5-9.8c-13.1-39.1-39.5-72-74.1-92.4zm-213.4 129c-26.5 0-48-21.5-48-48s21.5-48 48-48 48 21.5 48 48-21.5 48-48 48z"/></svg>
                        <h1 class="my-5 text-2xl font-bold ">Infectologia</h1>
                        <p class="md:p-5 text-gray-600 font-sans   ">Las enfermedades infecciosas son y han sido siempre una importante causa de morbilidad y mortalidad en todo el mundo. La infectología es una subespecialidad de la medicina que surge con el objetivo de realizar un …</p>
                    </div>
                </div>
               
            </section>
        <!-- /Services  -->

        <!-- Latest News  -->
             <section class="servicios mt-5 font-montserrat text-center">
                <h1 class="text-center text-gray-600 font-montserrat text-2xl">Latest News</h1>
                <div class="md:flex p-5 justify-between">
                    <div class="pb-5 md:w-4/12 md:mx-5 news-card mx-auto m-5 bg-white w-11/12 relative  ">
                        <div class="card-header">
                            <img src="../assets/img/bg_1.jpg" alt="">
                            <div class="bg-secondary text-white text-xl w-3/12 p-2 absolute top-0">
                                <p>Nov</p>
                                <p>28</p> 
                            </div>
                            
                        </div>

                        <div class="card-text p-5">
                            <h1 class="my-2 text-xl font-montserrat font-thin font-semibold">Lorem ipsum dolor sit </h1>
                            <p class=" text-lg text-gray-600 font-sans   ">Lorem ipsum dolor adipisicing amet, consectetur sit elit. Aspernatur incidihil quo officia.</p>
                        </div>

                        <div class="card-btn mt-5 flex justify-between px-5">
                            <button class="px-5 py-2 text-white bg-secondary font-light">Read More</button>
                            <div class="social-card-btn text-secondary flex items-center">
                                <div class="flex px-2">
                                    <svg aria-hidden="true" 
                                    data-prefix="fas" 
                                    data-icon="thumbs-up"
                                    class="h-5 w-5 svg-inline--fa fa-thumbs-up fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M104 224H24c-13.255 0-24 10.745-24 24v240c0 13.255 10.745 24 24 24h80c13.255 0 24-10.745 24-24V248c0-13.255-10.745-24-24-24zM64 472c-13.255 0-24-10.745-24-24s10.745-24 24-24 24 10.745 24 24-10.745 24-24 24zM384 81.452c0 42.416-25.97 66.208-33.277 94.548h101.723c33.397 0 59.397 27.746 59.553 58.098.084 17.938-7.546 37.249-19.439 49.197l-.11.11c9.836 23.337 8.237 56.037-9.308 79.469 8.681 25.895-.069 57.704-16.382 74.757 4.298 17.598 2.244 32.575-6.148 44.632C440.202 511.587 389.616 512 346.839 512l-2.845-.001c-48.287-.017-87.806-17.598-119.56-31.725-15.957-7.099-36.821-15.887-52.651-16.178-6.54-.12-11.783-5.457-11.783-11.998v-213.77c0-3.2 1.282-6.271 3.558-8.521 39.614-39.144 56.648-80.587 89.117-113.111 14.804-14.832 20.188-37.236 25.393-58.902C282.515 39.293 291.817 0 312 0c24 0 72 8 72 81.452z"/></svg>
                                    <span class="text-gray-800">5</span>
                                </div>
                                <div class="flex px-2">
                                    <svg 
                                        aria-hidden="true" data-prefix="fab" 
                                        data-icon="twitter" 
                                        class="h-5 w-5 svg-inline--fa fa-twitter fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"/></svg>
                                        <span class="text-gray-800">10</span>
                                </div>
                            </div>
                        </div>
                    </div>
                
                    <div class="pb-5 md:w-4/12 md:mx-5 news-card mx-auto m-5 bg-white w-11/12 relative  ">
                        <div class="card-header">
                            <img src="../assets/img/bg_2.jpg" alt="">
                            <div class="bg-secondary text-white text-xl w-3/12 p-2 absolute top-0">
                                <p>Nov</p>
                                <p>28</p> 
                            </div>
                            
                        </div>
                        <div class="card-text p-5">
                            <h1 class="my-2 text-xl font-montserrat font-thin font-semibold">Lorem ipsum dolor sit </h1>
                        <p class=" text-lg text-gray-600 font-sans   ">Lorem ipsum dolor adipisicing amet, consectetur sit elit. Aspernatur incidihil quo officia.</p>
                        </div>

                        <div class="card-btn mt-5 flex justify-between px-5">
                            <button class="px-5 py-2 text-white bg-secondary font-light">Read More</button>
                            <div class="social-card-btn text-secondary flex items-center">
                                <div class="flex px-2">
                                    <svg aria-hidden="true" 
                                    data-prefix="fas" 
                                    data-icon="thumbs-up"
                                    class="h-5 w-5 svg-inline--fa fa-thumbs-up fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M104 224H24c-13.255 0-24 10.745-24 24v240c0 13.255 10.745 24 24 24h80c13.255 0 24-10.745 24-24V248c0-13.255-10.745-24-24-24zM64 472c-13.255 0-24-10.745-24-24s10.745-24 24-24 24 10.745 24 24-10.745 24-24 24zM384 81.452c0 42.416-25.97 66.208-33.277 94.548h101.723c33.397 0 59.397 27.746 59.553 58.098.084 17.938-7.546 37.249-19.439 49.197l-.11.11c9.836 23.337 8.237 56.037-9.308 79.469 8.681 25.895-.069 57.704-16.382 74.757 4.298 17.598 2.244 32.575-6.148 44.632C440.202 511.587 389.616 512 346.839 512l-2.845-.001c-48.287-.017-87.806-17.598-119.56-31.725-15.957-7.099-36.821-15.887-52.651-16.178-6.54-.12-11.783-5.457-11.783-11.998v-213.77c0-3.2 1.282-6.271 3.558-8.521 39.614-39.144 56.648-80.587 89.117-113.111 14.804-14.832 20.188-37.236 25.393-58.902C282.515 39.293 291.817 0 312 0c24 0 72 8 72 81.452z"/></svg>
                                    <span class="text-gray-800">5</span>
                                </div>
                                <div class="flex px-2">
                                    <svg 
                                        aria-hidden="true" data-prefix="fab" 
                                        data-icon="twitter" 
                                        class="h-5 w-5 svg-inline--fa fa-twitter fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"/></svg>
                                        <span class="text-gray-800">10</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="pb-5 md:w-4/12 md:mx-5 news-card mx-auto m-5 bg-white w-11/12 relative  ">
                        <div class="card-header">
                            <img src="../assets/img/bg_3.jpg" alt="">
                            <div class="bg-secondary text-white text-xl w-3/12 p-2 absolute top-0">
                                <p>Nov</p>
                                <p>28</p> 
                            </div>
                            
                        </div>
                        <div class="card-text p-5">
                            <h1 class="my-2 text-xl font-montserrat font-thin font-semibold">Lorem ipsum dolor sit </h1>
                        <p class=" text-lg text-gray-600 font-sans   ">Lorem ipsum dolor adipisicing amet, consectetur sit elit. Aspernatur incidihil quo officia.</p>
                        </div>

                        <div class="card-btn mt-5 flex justify-between px-5">
                            <button class="px-5 py-2 text-white bg-secondary font-light">Read More</button>
                            <div class="social-card-btn text-secondary flex items-center">
                                <div class="flex px-2">
                                    <svg aria-hidden="true" 
                                    data-prefix="fas" 
                                    data-icon="thumbs-up"
                                    class="h-5 w-5 svg-inline--fa fa-thumbs-up fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M104 224H24c-13.255 0-24 10.745-24 24v240c0 13.255 10.745 24 24 24h80c13.255 0 24-10.745 24-24V248c0-13.255-10.745-24-24-24zM64 472c-13.255 0-24-10.745-24-24s10.745-24 24-24 24 10.745 24 24-10.745 24-24 24zM384 81.452c0 42.416-25.97 66.208-33.277 94.548h101.723c33.397 0 59.397 27.746 59.553 58.098.084 17.938-7.546 37.249-19.439 49.197l-.11.11c9.836 23.337 8.237 56.037-9.308 79.469 8.681 25.895-.069 57.704-16.382 74.757 4.298 17.598 2.244 32.575-6.148 44.632C440.202 511.587 389.616 512 346.839 512l-2.845-.001c-48.287-.017-87.806-17.598-119.56-31.725-15.957-7.099-36.821-15.887-52.651-16.178-6.54-.12-11.783-5.457-11.783-11.998v-213.77c0-3.2 1.282-6.271 3.558-8.521 39.614-39.144 56.648-80.587 89.117-113.111 14.804-14.832 20.188-37.236 25.393-58.902C282.515 39.293 291.817 0 312 0c24 0 72 8 72 81.452z"/></svg>
                                    <span class="text-gray-800">5</span>
                                </div>
                                <div class="flex px-2">
                                    <svg 
                                        aria-hidden="true" data-prefix="fab" 
                                        data-icon="twitter" 
                                        class="h-5 w-5 svg-inline--fa fa-twitter fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"/></svg>
                                        <span class="text-gray-800">10</span>
                                </div>
                            </div>
                        </div>
                    </div>
                     
                </div>
             </section>

        <!-- /Latest News  -->

        <!-- Team  -->

        <section class="team mt-5 text-center">
                <h1 class="text-center text-gray-600 font-montserrat text-2xl">Our Team</h1>
            <carousel  
                :centerMode="true"
                :easing="fadeIn"    
                :loop="true" :autoplay="true" :perPage="1" :interval="3000"  >
                <slide >
                    <div class="card mt-5 w-full md:w-4/12 p-5 mx-auto">
                        <div class="avatar mx-auto ">
                            <img class="border-orange-500 border-4 rounded-full" src="../assets/img/person_1.jpg" alt="">
                        </div>
                        <div>
                            <h1 class="text-2xl font-semibold">Dra. Juana Perez</h1>
                            <p class="italic font-light p-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate eius illum, distinctio sunt atque veritatis cupiditate possimus velit nulla tempore at! Tempora unde repellendus atque sapiente vitae molestias delectus perspiciatis.</p>
                        </div>
                    </div>
                </slide>
                <slide >
                    <div class="card mt-5 w-full md:w-4/12 p-5 mx-auto">
                        <div class="avatar mx-auto ">
                            <img class="border-orange-500 border-4 rounded-full" src="../assets/img/person_2.jpg" alt="">
                        </div>
                        <div>
                            <h1 class="text-2xl font-semibold">Dr. Juan Perez</h1>
                            <p class="italic font-light p-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate eius illum, distinctio sunt atque veritatis cupiditate possimus velit nulla tempore at! Tempora unde repellendus atque sapiente vitae molestias delectus perspiciatis.</p>
                        </div>
                    </div>
                </slide>
                <slide >
                    <div class="card mt-5 w-full md:w-4/12 p-5 mx-auto">
                        <div class="avatar mx-auto ">
                            <img class="border-orange-500 border-4 rounded-full" src="../assets/img/person_3.jpg" alt="">
                        </div>
                        <div>
                            <h1 class="text-2xl font-semibold">Dra. Jhon Doe</h1>
                            <p class="italic font-light p-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate eius illum, distinctio sunt atque veritatis cupiditate possimus velit nulla tempore at! Tempora unde repellendus atque sapiente vitae molestias delectus perspiciatis.</p>
                        </div>
                    </div>
                </slide>
                
            </carousel>
            
                
                    <!-- <div class="card mt-5">
                        <div class="avatar w-4/12 mx-auto ">
                            <img class="border-orange-500 border-4 rounded-full" src="../assets/img/person_1.jpg" alt="">
                        </div>
                    
                    <h1 class="text-2xl font-semibold">Dra. Juana Perez</h1>
                    <p class="italic font-light p-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate eius illum, distinctio sunt atque veritatis cupiditate possimus velit nulla tempore at! Tempora unde repellendus atque sapiente vitae molestias delectus perspiciatis.</p>

                    </div> -->
                                        
        </section>

        <!-- Team  -->

        <!-- Contact  -->
        <section class="contact flex">
            <div class="hidden md:block md:w-6/12 bg-secondary p-10 text-white">
                <h2 class="text-3xl font-semibold">In Search Of A Good And Quality Medical Hospital supporting team aids in providing oral health services.</h2>
                <p class="py-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque commodi molestiae autem fugit consectetur dolor ullam illo ipsa numquam, quod iusto enim ipsum amet iusto amet consec utem fugit consllo ipsa numquam dolor ullam illo, quod iusto enim ipsum amet iusto amet consec.</p> 

                <button class="bg-gray-200 px-5 py-2 rounded-full text-gray-900 hover:bg-gray-500 hover:text-white">view details</button>  
            </div>
            <div class="w-full md:w-6/12 bg-gray-400 p-5 md:p-10 text-white">
                <h1 class="text-gray-600 font-montserrat text-2xl">Contact Now</h1>
                <div class="mb-5 border-2 w-3/12 border-orange-500">                   
                </div>
                <form action="">
                    <input class="text-lg h-12 p-5 w-full text-gray-900" type="text" placeholder="Enter Name">
                    <div class="md:flex my-5 justify-between ">
                         <input type="text" placeholder="Email" class="mr-5 mb-5 md:mb-0 text-lg h-12 p-5 w-full text-gray-900">
                         <input type="text" placeholder="Phone" class="text-lg h-12 p-5 w-full text-gray-900">
                    </div>
                    <div class="md:flex my-5 justify-between ">
                        <select class="mb-5 md:mb-0 block appearance-none mr-5 text-lg h-12 p-5 w-full text-gray-900" name="" id="">
                            <option value="" class="bg-white text-sm ">Opcion 1</option>
                            <option value="" class="bg-white text-sm">Opcion 1</option>
                            <option value="" class="bg-white text-sm">Opcion 1</option>
                        </select>
                         <input type="text" placeholder="phone" class="text-lg h-12 p-5 w-full text-gray-900">
                    </div>
                    <button class="px-5 py-2 text-white bg-secondary font-semibold">Submit Now</button>
               </form>
            </div>
        </section>
        <!-- /Contact  -->
      </main>

    <footer class="bg-gray-900">
        <div class="md:flex items-center">
            <div class="brand flex justify-center p-5 items-center">
                <div class="bg-orange-600 rounded-full p-4 bg-logo bg-cover ">
                    <svg aria-hidden="true" data-prefix="fas" 
                    data-icon="microscope" 
                    class="text-white h-8 w-8 svg-inline--fa fa-microscope fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M160 320h12v16c0 8.84 7.16 16 16 16h40c8.84 0 16-7.16 16-16v-16h12c17.67 0 32-14.33 32-32V64c0-17.67-14.33-32-32-32V16c0-8.84-7.16-16-16-16h-64c-8.84 0-16 7.16-16 16v16c-17.67 0-32 14.33-32 32v224c0 17.67 14.33 32 32 32zm304 128h-1.29C493.24 413.99 512 369.2 512 320c0-105.88-86.12-192-192-192v64c70.58 0 128 57.42 128 128s-57.42 128-128 128H48c-26.51 0-48 21.49-48 48 0 8.84 7.16 16 16 16h480c8.84 0 16-7.16 16-16 0-26.51-21.49-48-48-48zm-360-32h208c4.42 0 8-3.58 8-8v-16c0-4.42-3.58-8-8-8H104c-4.42 0-8 3.58-8 8v16c0 4.42 3.58 8 8 8z"/></svg>
                </div>
                <div class="mx-2">
                    <h2 class="font-montserrat text-gray-100">LAB CM</h2>
                    <span class="text-xs text-gray-500">Lab. Analisis Clinicos</span>
                </div>
            </div>

            <p class="md:w-3/12 text-xs text-gray-500 p-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut suscipit adipisci reiciendis? Molestias ipsam dolorem possimus minus fuga, facilis at esse quam obcaecati rerum magnam atque nemo vel similique voluptates.</p>
              
            <div class="info text-gray-500 px-5">
                <div class="flex items-center">
                    <svg aria-hidden="true" data-prefix="fas" 
                    data-icon="map-marker-alt" 
                    class="h-5 w-5 text-orange-600 svg-inline--fa fa-map-marker-alt fa-w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><path fill="currentColor" d="M172.268 501.67C26.97 291.031 0 269.413 0 192 0 85.961 85.961 0 192 0s192 85.961 192 192c0 77.413-26.97 99.031-172.268 309.67-9.535 13.774-29.93 13.773-39.464 0zM192 272c44.183 0 80-35.817 80-80s-35.817-80-80-80-80 35.817-80 80 35.817 80 80 80z"/></svg>
                    <p class="mx-5 font-montserrat font-thin">Balcarce 234, Villa Angela(3540) Chaco</p>
                </div>
                <div class="flex items-center">
                <svg aria-hidden="true" 
                    data-prefix="fas" 
                    data-icon="phone" 
                    class="h-5 w-5 text-orange-600 svg-inline--fa fa-phone fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M493.4 24.6l-104-24c-11.3-2.6-22.9 3.3-27.5 13.9l-48 112c-4.2 9.8-1.4 21.3 6.9 28l60.6 49.6c-36 76.7-98.9 140.5-177.2 177.2l-49.6-60.6c-6.8-8.3-18.2-11.1-28-6.9l-112 48C3.9 366.5-2 378.1.6 389.4l24 104C27.1 504.2 36.7 512 48 512c256.1 0 464-207.5 464-464 0-11.2-7.7-20.9-18.6-23.4z"/></svg>
                <p class="mx-5 font-montserrat font-thin">+54 9 3735 420629</p>
                </div>
                <div class="flex items-center">
                    <svg aria-hidden="true" data-prefix="fas" 
                    data-icon="envelope" 
                    class="h-5 w-5 text-orange-600 svg-inline--fa fa-envelope fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M502.3 190.8c3.9-3.1 9.7-.2 9.7 4.7V400c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V195.6c0-5 5.7-7.8 9.7-4.7 22.4 17.4 52.1 39.5 154.1 113.6 21.1 15.4 56.7 47.8 92.2 47.6 35.7.3 72-32.8 92.3-47.6 102-74.1 131.6-96.3 154-113.7zM256 320c23.2.4 56.6-29.2 73.4-41.4 132.7-96.3 142.8-104.7 173.4-128.7 5.8-4.5 9.2-11.5 9.2-18.9v-19c0-26.5-21.5-48-48-48H48C21.5 64 0 85.5 0 112v19c0 7.4 3.4 14.3 9.2 18.9 30.6 23.9 40.7 32.4 173.4 128.7 16.8 12.2 50.2 41.8 73.4 41.4z"/></svg>
                    <p class="mx-5 font-montserrat font-thin">admin@mail.com</p>
                </div>
                <div class="flex items-center">
                <svg aria-hidden="true" data-prefix="fas" 
                    data-icon="globe-americas" class="h-5 w-5 text-orange-600 svg-inline--fa fa-globe-americas fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512"><path fill="currentColor" d="M248 8C111.03 8 0 119.03 0 256s111.03 248 248 248 248-111.03 248-248S384.97 8 248 8zm82.29 357.6c-3.9 3.88-7.99 7.95-11.31 11.28-2.99 3-5.1 6.7-6.17 10.71-1.51 5.66-2.73 11.38-4.77 16.87l-17.39 46.85c-13.76 3-28 4.69-42.65 4.69v-27.38c1.69-12.62-7.64-36.26-22.63-51.25-6-6-9.37-14.14-9.37-22.63v-32.01c0-11.64-6.27-22.34-16.46-27.97-14.37-7.95-34.81-19.06-48.81-26.11-11.48-5.78-22.1-13.14-31.65-21.75l-.8-.72a114.792 114.792 0 01-18.06-20.74c-9.38-13.77-24.66-36.42-34.59-51.14 20.47-45.5 57.36-82.04 103.2-101.89l24.01 12.01C203.48 89.74 216 82.01 216 70.11v-11.3c7.99-1.29 16.12-2.11 24.39-2.42l28.3 28.3c6.25 6.25 6.25 16.38 0 22.63L264 112l-10.34 10.34c-3.12 3.12-3.12 8.19 0 11.31l4.69 4.69c3.12 3.12 3.12 8.19 0 11.31l-8 8a8.008 8.008 0 01-5.66 2.34h-8.99c-2.08 0-4.08.81-5.58 2.27l-9.92 9.65a8.008 8.008 0 00-1.58 9.31l15.59 31.19c2.66 5.32-1.21 11.58-7.15 11.58h-5.64c-1.93 0-3.79-.7-5.24-1.96l-9.28-8.06a16.017 16.017 0 00-15.55-3.1l-31.17 10.39a11.95 11.95 0 00-8.17 11.34c0 4.53 2.56 8.66 6.61 10.69l11.08 5.54c9.41 4.71 19.79 7.16 30.31 7.16s22.59 27.29 32 32h66.75c8.49 0 16.62 3.37 22.63 9.37l13.69 13.69a30.503 30.503 0 018.93 21.57 46.536 46.536 0 01-13.72 32.98zM417 274.25c-5.79-1.45-10.84-5-14.15-9.97l-17.98-26.97a23.97 23.97 0 010-26.62l19.59-29.38c2.32-3.47 5.5-6.29 9.24-8.15l12.98-6.49C440.2 193.59 448 223.87 448 256c0 8.67-.74 17.16-1.82 25.54L417 274.25z"/></svg>
                <p class="mx-5 font-montserrat font-thin">www.sitio.com</p>   
                </div>
            </div>

            <div class="text-gray-500 p-5">
                <h2 class="text-lg">Opening Hours</h2>
                <div class="text-sm text-gray-500 flex justify-between border-t border-orange-500">
                    <p>Mon - Fri</p>
                    <p>7.30am - 12.00 am</p>
                </div>
                <div class="text-sm text-gray-500 flex justify-between border-t  border-orange-500">
                    <p>Mon - Fri</p>
                    <p>17.30pm - 20.00 am</p>
                </div>
                <div class="text-sm text-white flex justify-between border-t border-b border-orange-500">
                    <p>Sat</p>
                    <p>7.30am - 12.00 am</p>
                </div>
            </div>

            <div>                    
                <h2 class="text-lg text-gray-200 px-5">Subscribe Us</h2>

                <form action="" class="flex items-center p-5">
                    <input type="text" placeholder="Email" 
                            class="p-2 w-full text-gray-900">
                    <button class="p-2 text-white bg-secondary ">Subscribe </button>

                </form>
                
            </div>

        </div>
    </footer>   
  </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel';
export default {
    components: {
    Carousel,
    Slide
  },
    data(){
        return{
           shown:false
        }
    },
    methods:{
        showMenu(){
            
        }
    }

}
</script>

<style>
    .hero{
        background-image: url('../assets/img/bg_4.jpg');
    }
    .bg-logo{
        background-image: url('../assets/img/icons/logo-bg.svg');
        color: white;
        background-repeat: no-repeat;
        
    }
    .hidden{
       transition: opacity .5s;
    }
</style>