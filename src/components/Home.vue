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
                  <div class="text-primary px-2">
                      <svg aria-hidden="true" data-prefix="fas" 
                      data-icon="microscope" 
                      class="h-16 w-16 svg-inline--fa fa-microscope fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M160 320h12v16c0 8.84 7.16 16 16 16h40c8.84 0 16-7.16 16-16v-16h12c17.67 0 32-14.33 32-32V64c0-17.67-14.33-32-32-32V16c0-8.84-7.16-16-16-16h-64c-8.84 0-16 7.16-16 16v16c-17.67 0-32 14.33-32 32v224c0 17.67 14.33 32 32 32zm304 128h-1.29C493.24 413.99 512 369.2 512 320c0-105.88-86.12-192-192-192v64c70.58 0 128 57.42 128 128s-57.42 128-128 128H48c-26.51 0-48 21.49-48 48 0 8.84 7.16 16 16 16h480c8.84 0 16-7.16 16-16 0-26.51-21.49-48-48-48zm-360-32h208c4.42 0 8-3.58 8-8v-16c0-4.42-3.58-8-8-8H104c-4.42 0-8 3.58-8 8v16c0 4.42 3.58 8 8 8z"/></svg>
                  </div>
                  <div>
                      <h2 class="font-montserrat">LAB MC</h2>
                      <span class="text-xs text-gray-500">Lab. Analisis Clinicos</span>
                  </div>
              </div>

              <div class="text-center text-sm py-2 md:flex items-center">
                  <svg aria-hidden="true" data-prefix="fas" data-icon="envelope" 
                    class="text-secondary mx-auto h-8 w-8 svg-inline--fa fa-envelope fa-w-16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M502.3 190.8c3.9-3.1 9.7-.2 9.7 4.7V400c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V195.6c0-5 5.7-7.8 9.7-4.7 22.4 17.4 52.1 39.5 154.1 113.6 21.1 15.4 56.7 47.8 92.2 47.6 35.7.3 72-32.8 92.3-47.6 102-74.1 131.6-96.3 154-113.7zM256 320c23.2.4 56.6-29.2 73.4-41.4 132.7-96.3 142.8-104.7 173.4-128.7 5.8-4.5 9.2-11.5 9.2-18.9v-19c0-26.5-21.5-48-48-48H48C21.5 64 0 85.5 0 112v19c0 7.4 3.4 14.3 9.2 18.9 30.6 23.9 40.7 32.4 173.4 128.7 16.8 12.2 50.2 41.8 73.4 41.4z"/></svg>
                    <div class="md:text-left md:px-2">
                        <p class="text-gray-500 uppercase">Mail us today</p>
                        <p class="font-semibold">info@domain.com</p>

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
              <ul class="text-gray-500 px-5 md:flex text-lg justify-around md:py-5 md:text-center">
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
                  <button class="hover:bg-orange-500 hover:text-secondary uppercase font-semibold md:text-xl rounded-full py-2 md:my-10 md:py-5 px-10 bg-secondary text-white">Contact</button>
              </div>
          </section>
        <!-- /hero  -->

        <!-- Services  -->
            <section class="servicios mt-5 font-montserrat text-center">
                <h1 class="text-center font-montserrat text-2xl">Our Servcices</h1>
                <div class="md:flex">
                    <div class="text-secondary w-full p-5 ">
                        <svg aria-hidden="true" data-prefix="fas" data-icon="viruses" 
                            class="mx-auto text-orange-500 h-10 w-10 svg-inline--fa fa-viruses fa-w-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512"><path fill="currentColor" d="M624 352h-12.12c-28.51 0-42.79-34.47-22.63-54.63l8.58-8.57a16 16 0 10-22.63-22.63l-8.57 8.58c-20.16 20.16-54.63 5.88-54.63-22.63V240a16 16 0 00-32 0v12.12c0 28.51-34.47 42.79-54.63 22.63l-8.57-8.58a16 16 0 00-22.63 22.63l8.58 8.57c20.16 20.16 5.88 54.63-22.63 54.63H368a16 16 0 000 32h12.12c28.51 0 42.79 34.47 22.63 54.63l-8.58 8.57a16 16 0 1022.63 22.63l8.57-8.58c20.16-20.16 54.63-5.88 54.63 22.63V496a16 16 0 0032 0v-12.12c0-28.51 34.47-42.79 54.63-22.63l8.57 8.58a16 16 0 1022.63-22.63l-8.58-8.57c-20.16-20.16-5.88-54.63 22.63-54.63H624a16 16 0 000-32zm-144 32a32 32 0 1132-32 32 32 0 01-32 32zM346.51 213.33h16.16a21.33 21.33 0 000-42.66h-16.16c-38 0-57.05-46-30.17-72.84l11.43-11.44a21.33 21.33 0 00-30.17-30.16l-11.43 11.43c-26.88 26.88-72.84 7.85-72.84-30.17V21.33a21.33 21.33 0 00-42.66 0v16.16c0 38-46 57.05-72.84 30.17L86.4 56.23a21.33 21.33 0 00-30.17 30.16l11.43 11.44c26.88 26.88 7.85 72.84-30.17 72.84H21.33a21.33 21.33 0 000 42.66h16.16c38 0 57.05 46 30.17 72.84L56.23 297.6a21.33 21.33 0 1030.17 30.17l11.43-11.43c26.88-26.88 72.84-7.85 72.84 30.17v16.16a21.33 21.33 0 0042.66 0v-16.16c0-38 46-57.05 72.84-30.17l11.43 11.43a21.33 21.33 0 0030.17-30.17l-11.43-11.43c-26.88-26.88-7.85-72.84 30.17-72.84zM160 192a32 32 0 1132-32 32 32 0 01-32 32zm80 32a16 16 0 1116-16 16 16 0 01-16 16z"/></svg>
                        <h1 class=" text-xl font-bold ">Bacteriologia</h1>
                        <p class="text-gray-600 font-sans   ">Se define como la ciencia que estudia las bacterias, en el área bacteriológica de Laboratorios AC desarrollamos las técnicas de diagnóstico directo e indirecto de las infecciones ocasionadas por bacterias y también por hongos.</p>
                    </div>

                    <div class="text-secondary w-full p-5 ">
                        <svg aria-hidden="true" data-prefix="fas" data-icon="notes-medical" 
                            class="mx-auto text-orange-500 h-10 w-10 svg-inline--fa fa-notes-medical fa-w-12" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><path fill="currentColor" d="M336 64h-80c0-35.3-28.7-64-64-64s-64 28.7-64 64H48C21.5 64 0 85.5 0 112v352c0 26.5 21.5 48 48 48h288c26.5 0 48-21.5 48-48V112c0-26.5-21.5-48-48-48zM192 40c13.3 0 24 10.7 24 24s-10.7 24-24 24-24-10.7-24-24 10.7-24 24-24zm96 304c0 4.4-3.6 8-8 8h-56v56c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8v-56h-56c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h56v-56c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v56h56c4.4 0 8 3.6 8 8v48zm0-192c0 4.4-3.6 8-8 8H104c-4.4 0-8-3.6-8-8v-16c0-4.4 3.6-8 8-8h176c4.4 0 8 3.6 8 8v16z"/></svg>
                        <h1 class=" text-xl font-bold ">Bioq. Clinica</h1>
                        <p class="text-gray-600 font-sans   ">La bioquímica clínica es la rama del laboratorio en la que se usan métodos químicos y bioquímicos para el estudio de las enfermedades. En la práctica, está usualmente dedicada a los estudios de la sangre, orina y otros fluidos biológicos …</p>
                    </div>

                    <div class="text-secondary w-full p-5 ">
                        <svg aria-hidden="true" data-prefix="fas" 
                        data-icon="biohazard" class="mx-auto text-orange-500 h-10 w-10svg-inline--fa fa-biohazard fa-w-18" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512"><path fill="currentColor" d="M287.9 112c18.6 0 36.2 3.8 52.8 9.6 13.3-10.3 23.6-24.3 29.5-40.7-25.2-10.9-53-17-82.2-17-29.1 0-56.9 6-82.1 16.9 5.9 16.4 16.2 30.4 29.5 40.7 16.5-5.7 34-9.5 52.5-9.5zM163.6 438.7c12-11.8 20.4-26.4 24.5-42.4-32.9-26.4-54.8-65.3-58.9-109.6-8.5-2.8-17.2-4.6-26.4-4.6-7.6 0-15.2 1-22.5 3.1 4.1 62.8 35.8 118 83.3 153.5zm224.2-42.6c4.1 16 12.5 30.7 24.5 42.5 47.4-35.5 79.1-90.7 83-153.5-7.2-2-14.7-3-22.2-3-9.2 0-18 1.9-26.6 4.7-4.1 44.2-26 82.9-58.7 109.3zm113.5-205c-17.6-10.4-36.3-16.6-55.3-19.9 6-17.7 10-36.4 10-56.2 0-41-14.5-80.8-41-112.2-2.5-3-6.6-3.7-10-1.8-3.3 1.9-4.8 6-3.6 9.7 4.5 13.8 6.6 26.3 6.6 38.5 0 67.8-53.8 122.9-120 122.9S168 117 168 49.2c0-12.1 2.2-24.7 6.6-38.5 1.2-3.7-.3-7.8-3.6-9.7-3.4-1.9-7.5-1.2-10 1.8C134.6 34.2 120 74 120 115c0 19.8 3.9 38.5 10 56.2-18.9 3.3-37.7 9.5-55.3 19.9-34.6 20.5-61 53.3-74.3 92.4-1.3 3.7.2 7.7 3.5 9.8 3.3 2 7.5 1.3 10-1.6 9.4-10.8 19-19.1 29.2-25.1 57.3-33.9 130.8-13.7 163.9 45 33.1 58.7 13.4 134-43.9 167.9-10.2 6.1-22 10.4-35.8 13.4-3.7.8-6.4 4.2-6.4 8.1.1 4 2.7 7.3 6.5 8 39.7 7.8 80.6.8 115.2-19.7 18-10.6 32.9-24.5 45.3-40.1 12.4 15.6 27.3 29.5 45.3 40.1 34.6 20.5 75.5 27.5 115.2 19.7 3.8-.7 6.4-4 6.5-8 0-3.9-2.6-7.3-6.4-8.1-13.9-2.9-25.6-7.3-35.8-13.4-57.3-33.9-77-109.2-43.9-167.9s106.6-78.9 163.9-45c10.2 6.1 19.8 14.3 29.2 25.1 2.5 2.9 6.7 3.6 10 1.6s4.8-6.1 3.5-9.8c-13.1-39.1-39.5-72-74.1-92.4zm-213.4 129c-26.5 0-48-21.5-48-48s21.5-48 48-48 48 21.5 48 48-21.5 48-48 48z"/></svg>
                        <h1 class=" text-xl font-bold ">Infectologia</h1>
                        <p class="text-gray-600 font-sans   ">Las enfermedades infecciosas son y han sido siempre una importante causa de morbilidad y mortalidad en todo el mundo. La infectología es una subespecialidad de la medicina que surge con el objetivo de realizar un …</p>
                    </div>
                </div>
               
            </section>
        <!-- /Services  -->

        <!-- Team  -->

            <section class="team mt-5 text-center">
                <h1 class="font-montserrat text-2xl">Our Team</h1>
                <div class="card mt-5">
                    <div class="avatar w-4/12 mx-auto ">
                        <img class="border-orange-500 border-4 rounded-full" src="../assets/img/person_1.jpg" alt="">
                    </div>
                    <div>
                    <h1 class="text-2xl font-semibold">Dra. Juana Perez</h1>
                    <p class="italic font-light p-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate eius illum, distinctio sunt atque veritatis cupiditate possimus velit nulla tempore at! Tempora unde repellendus atque sapiente vitae molestias delectus perspiciatis.</p>
 
                    </div>
                   
                </div>
               
            </section>

        <!-- Team  -->
      </main>   
  </div>
</template>

<script>
export default {

}
</script>

<style>
    .hero{
        background-image: url('../assets/img/bg_4.jpg');
    }
</style>