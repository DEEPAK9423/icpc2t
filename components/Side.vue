<template>
  <!-- Sidebar -->
  <div class="col-xl-4 col-md-12 widget-column mt-0">
    <!-- Section: Categories -->
    <section class="section mb-5">
      <h4 class="mt-2 text-center">
        <strong>ANNOUNCEMENT</strong>
      </h4>

      <hr class="red title-hr" />
      <div class="card card-body d-flex text-center">
        <p class="card-text red-text">
          <marquee
            direction="up"
            height="150px"
            scrollamount="2"
            scrolldelay="3"
            onmouseover="this.stop();"
            onmouseout="this.start();"
          >
            Deadline for Full Paper Submission :
            30<sup>th</sup> August 2023 <br /><br />
            Venue : Department of Electrical Engineering, National Institute of
            Technology, Raipur, India
            <br /><br />
            Submission Information : The Conference Management Toolkit (CMT)
            sponsored by Microsoft Research (<a
              href="https://cmt3.research.microsoft.com/ICPC2T2022"
              target="_blank"
              >click here</a
            >)
          </marquee>
        </p>
      </div>
    </section>
    <!-- Section: Categories -->

    <hr class="my-3" />
    <!-- Section: Advertisment -->
    <section class="section mt-5">
      <!-- Jumbotron -->

      <h4 class="mt-2 text-center">
        <strong>IMPORTANT DATES</strong>
      </h4>
      <hr class="red title-hr" />
      <ul class="list-group z-depth-1 mt-4">
        <li class="list-group-item">
          Paper Submission starts :
          30<sup>th</sup> June 2023 <br /><br />
        </li>
        <li class="list-group-item">
          Deadline for Full Paper Submission :
          30<sup>th</sup> August 2023 <br /><br />
        </li>
        <li class="list-group-item">
          Acceptance Notification : 30<sup>th</sup> October
          2023
        </li>
        <li class="list-group-item">
          Camera Ready Paper Submission : 30<sup>th</sup>
          November 2023
        </li>
        <li class="list-group-item">
          Registration Deadline : 20<sup>th</sup> December 2023
        </li>
      </ul>
      <!-- Text -->
      <hr class="my-3" />
      <!-- Jumbotron -->
    </section>
    <!-- Section: Advertisment -->
    <!-- <section class="section mb-5">
      <h4 class=" mt-2 text-center">
        <strong>Our Partners</strong>
      </h4>

      <hr class="red title-hr" />
      <div class="card card-body d-flex text-center">
        <p class="card-text red-text ">
        </p>
      </div>
    </section> -->
    <section class="section mb-5">
      <h4 class="mt-2 text-center">
        <strong>TECHNICAL SPONSORS</strong>
      </h4>

      <hr class="red title-hr" />
      <div class="card card-body d-flex text-center">
        <p class="card-text red-text">
          <carousel
            :per-page="1"
            :mouse-drag="true"
            :loop="true"
            :autoplay="true"
          >
            <slide>
              <img src="@/assets/partners/ieee_mp_section.jpg" alt="" />
            </slide>
            
            <slide>
              <img src="@/assets/partners/ieeespons.png" alt="" />
            </slide>
          </carousel>
        </p>
      </div>
    </section>
    <section class="section mb-5">
      <h4 class="mt-2 text-center">
        <strong>BROCHURE</strong>
      </h4>

      <hr class="red title-hr" />
      <div class="card card-body d-flex text-center">
        <p class="card-text blue-text">
          <a href="/brochure.pdf" target="_blank"
            >Download ICPC<sup>2</sup>T 2024 - Brochure
            <i class="fas fa-file-pdf"></i
          ></a>
        </p>
      </div>
    </section>
  </div>
  <!-- Sidebar -->
</template>

<script>
export default {
  name: "Side",
};
</script>
<style scoped>
img {
  width: 100%;
  height: 100%;
}
li:hover {
  background-color: rgb(184, 221, 248);
}
</style>
