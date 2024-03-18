<!DOCTYPE html>
<html>
  <title>Portfolio Template</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css" />
  <link
    rel="stylesheet"
    href="https://fonts.googleapis.com/css?family=Montserrat"
  />
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
  />
  <style>
    body,
    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
      font-family: "Montserrat", sans-serif;
    }
    .w3-row-padding img {
      margin-bottom: 12px;
    }
    .bgimg {
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      background-image: image-set("./face.jpg");
      min-height: 100%;
    }
  </style>
  <body>
    <!-- The Sidebar with image -->
    <nav class="w3-sidebar w3-hide-medium w3-hide-small" style="width: 40%">
      <div class="bgimg"></div>
    </nav>

    <!-- The Hidden Sidebar reveals when clicked on menu icon -->
    <nav
      class="w3-sidebar w3-black w3-animate-right w3-xxlarge"
      style="display: none; padding-top: 150px; right: 0; z-index: 2"
      id="mySidebar"
    >
      <a
        href="javascript:void(0)"
        onclick="closeNav()"
        class="w3-button w3-black w3-xxxlarge w3-display-topright"
        style="padding: 0 12px"
      >
        <i class="fa fa-remove"></i>
      </a>
      <div class="w3-bar-block w3-center">
        <a
          href="#"
          class="w3-bar-item w3-button w3-text-grey w3-hover-black"
          onclick="closeNav()"
          >Home</a
        >
        <a
          href="#welcome"
          class="w3-bar-item w3-button w3-text-grey w3-hover-black"
          onclick="closeNav()"
          >Welcome</a
        >
        <a
          href="#about"
          class="w3-bar-item w3-button w3-text-grey w3-hover-black"
          onclick="closeNav()"
          >About</a
        >
        <a
          href="#contact"
          class="w3-bar-item w3-button w3-text-grey w3-hover-black"
          onclick="closeNav()"
          >Contact</a
        >
      </div>
    </nav>

    <!-- The Page Content -->
    <div class="w3-main w3-padding-large" style="margin-left: 40%">
      <!-- The Menu icon to open sidebar -->
      <span
        class="w3-button w3-top w3-white w3-xxlarge w3-text-grey w3-hover-text-black"
        style="width: auto; right: 0"
        onclick="openNav()"
        ><i class="fa fa-bars"></i
      ></span>

      <!-- Header -->
      <header
        class="w3-container w3-center"
        style="padding: 35px 16px"
        id="home"
      >
        <h1 class="w3-jumbo"><b>Your Name</b></h1>
        <p>Rising Professional Editor.</p>
        <img
          src="./face.jpg"
          class="w3-image w3-hide-large w3-hide-small w3-round"
          style="display: block; width: 60%; margin: auto"
        />
        <img
          src="./face.jpg"
          class="w3-image w3-hide-large w3-hide-medium w3-round"
          width="1000"
          height="1333"
        />
      </header>

      <!-- The Welcome Section -->
      <div class="w3-padding-32 w3-content w3-text-grey" id="welcome">
        <h2 class="w3-text-grey">Welcome!</h2>
        <hr class="w3-opacity" />
        <p>
          This is a website I have created to showcase my skills and what I have
          to offer.
        </p>
      </div>

      <!-- About Section -->
      <div class="w3-content w3-justify w3-text-grey w3-padding-32" id="about">
        <h2>About Me</h2>
        <hr class="w3-opacity" />
        <p>
          I have been writting since a very young age which lead me to obtain my
          degree in proffesional litature. Soon after I found myslef to really
          enjoy editing and enheancing others writting which is what I do in
          most of my free time and insire to do one day full time.
        </p>
        <br>
        <h3 class="w3-padding-16">My Skills</h3>
        <p class="w3-wide">Technical Writing</p>
        <div class="w3-light-grey">
          <div
            class="w3-container w3-center w3-padding-small w3-dark-grey"
            style="width: 95%"
          >
            95%
          </div>
        </div>
        <p class="w3-wide">Editing</p>
        <div class="w3-light-grey">
          <div
            class="w3-container w3-center w3-padding-small w3-dark-grey"
            style="width: 85%"
          >
            85%
          </div>
        </div>
        <p class="w3-wide">Vocabulary</p>
        <div class="w3-light-grey">
          <div
            class="w3-container w3-center w3-padding-small w3-dark-grey"
            style="width: 80%"
          >
            80%
          </div>
        </div>
        <br />

        <div class="w3-row w3-center w3-dark-grey w3-padding-16 w3-section">
          <div class="w3-quarter w3-section">
            <span class="w3-xlarge">10+</span><br />
            Partners
          </div>
          <div class="w3-quarter w3-section">
            <span class="w3-xlarge">26+</span><br />
            Projects Done
          </div>
          <div class="w3-quarter w3-section">
            <span class="w3-xlarge">15+</span><br />
            Happy Clients
          </div>
          <div class="w3-quarter w3-section">
            <span class="w3-xlarge">3+</span><br />
            books
          </div>
        </div>

        <!-- The Experience Section -->
        <h3 class="w3-padding-24">My Experience</h3>
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSLvhsAQNXGL-E6mTDuzPIFTxu4Bg5Eo7Anqg&usqp=CAU"
          alt="Avatar"
          class="w3-left w3-circle w3-margin-right"
          style="width: 80px"
        />
        <p>
          <span class="w3-large w3-text-black w3-margin-right"
            >A Tale of Two Rivers</span
          >
          Auther & Editor
        </p>
        <p>
          This is a short story I have created currently sold 200+ copies on
          amazon
        </p>
        <br />

        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROVv4vnO42ROeWb9aYEiETGZQ9oLncyWh54g&usqp=CAU"
          alt="Avatar"
          class="w3-left w3-circle w3-margin-right"
          style="width: 80px"
        />
        <p>
          <span class="w3-large w3-text-black w3-margin-right"
            >30 Page Thesis</span
          >
          Auther
        </p>
        <p>
          For my final project at my school we had to create a thesis papper
          which mine consisted on the topic of enviormental energy
        </p>
        <br />

        <img
          src="https://www.decorilla.com/online-decorating/wp-content/uploads/2023/05/correcto.jpg"
          alt="Avatar"
          class="w3-left w3-circle w3-margin-right"
          style="width: 80px"
        />
        <p>
          <span class="w3-large w3-text-black w3-margin-right"
            >Part Time Intern</span
          >
          Write CORP
        </p>
        <p>
          Preformed editing duties for the senior editors at the firm for the
          clients
        </p>
        <br />

      <!-- The Contact Section -->
      <div
        class="w3-padding-32 w3-content w3-text-grey"
        id="contact"
        style="margin-bottom: 64px"
      >
        <h2>Contact Me</h2>
        <hr class="w3-opacity" />

        <div class="w3-section">
          <p>
            <i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i>
            Chicago, US
          </p>
          <p>
            <i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Phone:
            +00 151515
          </p>
          <p>
            <i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i>
            Email: mail@mail.com
          </p>
        </div>
      </div>
    </div>
      <!-- The Footer Section -->
    <div>
      <footer
        class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge"
        style="margin: -24px"
      >
        <p class="w3-medium">
          Last Updated 2024
        </p>
      </footer>
    </div>

    <script>
      // Open and close the sidebar
      function openNav() {
        document.getElementById("mySidebar").style.width = "60%";
        document.getElementById("mySidebar").style.display = "block";
      }

      function closeNav() {
        document.getElementById("mySidebar").style.display = "none";
      }
    </script>
  </body>
</html>
