<template>
  <footer class="footer" style="background-color: rgba(88, 188, 130, 0.1)">
    <div class="custom">
      <div class="custom-footer">
        <div class="custom-footer-content">
          <img src="" />
          <div class="custom-icons">
            <a href="#"><i class="bx bxl-instagram"></i></a>
          </div>
        </div>
        <div class="custom-footer-content">
          <h4>Associate with:</h4>
          <img
            src="../assets/icons/CIS_logo-removebg-preview.png"
            height="110"
            width="110"
          />
          <img
            src="../assets/icons/csd-removebg-preview.png"
            height="110"
            width="110"
          />
        </div>

        <div class="custom-footer-content">
          <h4>Department :</h4>
          <li><a href="#">Top</a></li>
          <li><a href="#">Level</a></li>
          <li><a href="#">Huge</a></li>
          <li><a href="#">Action</a></li>
        </div>

        <div class="custom-footer-content">
          <h4>Learn More</h4>
          <li><a href="#">Home</a></li>
          <li><a href="#">Event</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Want to Learn?</a></li>
        </div>

        <div class="custom-footer-content">
          <h4>Contact Us</h4>
          <li><a href="#">Secretary</a></li>
          <li><a href="#">Ram</a></li>
        </div>
        <div class="custom-footer-content">
          <h4>Social</h4>
          <li><a href="#">Instagram</a></li>
        </div>
      </div>
    </div>
  </footer>
  <div
    style="
      display: flex;
      align-items: center;
      justify-content: center;
      padding-top: 10px;
      padding-bottom: 10px;
      background-color: rgba(88, 188, 130, 0.1);
      color: black;
    "
  >
    @2023 Syntech | All Rights Reserved
  </div>
</template>

<style scoped>
.custom {
  padding: 0;
  margin: 0;
  text-decoration: none;
  list-style: none;
}

.custom-footer {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(0px, auto));

  position: relative;
  left: 0;
  right: 0;
  bottom: 0;
}

.custom-footer-content h4 {
  color: black; /*change back to white if want black footer */
  margin-bottom: 1.5rem;
  font-size: 20px;
  font-weight: 550;
}

.custom-footer-content li {
  margin-bottom: 16px;
}

.custom-footer-content li a {
  display: block;
  color: black;
  font-size: 15px;
  font-weight: 400;
  transition: all.40s ease;
}

.custom-footer-content li a:hover {
  transform: translateY(-3px) translateX(-5px);
  color: black;
}

.custom-icons a {
  display: inline-block;
  font-size: 22px;
  color: black;
  margin-right: 17px;
  transition: all 0.4s ease;
}
@keyframes tonext {
  75% {
    left: 0;
  }
  95% {
    left: 100%;
  }
  98% {
    left: 100%;
  }
  99% {
    left: 0;
  }
}

@keyframes tostart {
  75% {
    left: 0;
  }
  95% {
    left: -300%;
  }
  98% {
    left: -300%;
  }
  99% {
    left: 0;
  }
}

@keyframes snap {
  96% {
    scroll-snap-align: center;
  }
  97% {
    scroll-snap-align: none;
  }
  99% {
    scroll-snap-align: none;
  }
  100% {
    scroll-snap-align: center;
  }
}
</style>
