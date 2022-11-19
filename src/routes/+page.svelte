<script>
    import {fade} from "svelte/transition"
    import "../lib/Navbar.svelte"
    let visible = false;
    setTimeout(show, 1)
    function show(){
        visible = true;
    }
</script>
{#if visible}
<div class="contents" id="main" in:fade>
    <h1
        id="Home"
      style="
        margin-top: 200px;
        align-items: center;
        justify-content: center;
      "
    >
      We are Ohm Interactive.
    </h1>



    <p
      style="
        margin-top: 0%;
        margin-left: 40.5%;
        align-items: center;
        justify-content: center;
      "
    >
      ⠀
    </p>

    <div class="grid-container">
      <article id="3685" class="location-listing">
        <a
          class="location-title"
          href="https://www.youtube.com/channel/UCgJvTMmkvGkdRjoZl5hl4pw"
        >
          OmegaaDev
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="Omegaa.jpg"
              alt="OmegaaDev"
            />
          </div>
        </div>
      </article>

      <article id="3688" class="location-listing">
        <a
          class="location-title"
          href="https://www.youtube.com/c/Twingamerdudes"
        >
          TwinGamerDudes
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="Twingamerdudes.jpg"
              alt="TwinGamerDudes"
            />
          </div>
        </div>
      </article>

      <article id="3691" class="location-listing">
        <a
          class="location-title"
          href="https://www.youtube.com/channel/UCNrG1txeilrXxrDbiJClxCQ"
        >
          Inovade
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="Inovade.png"
              alt="Inovade"
            />
          </div>
        </div>
      </article>

      <article id="3694" class="location-listing">
        <a
          class="location-title"
          href="https://www.instagram.com/Mybuttitche5"
        >
          Nightmare
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="BigPoop.png"
              alt="Nightmare"
            />
          </div>
        </div>
      </article>

      <article id="3697" class="location-listing">
        <a class="location-title" href="https://discord.gg/UmFytm8M7a">
          Tob
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="Tob.png"
              alt="Tob"
            />
          </div>
        </div>
      </article>

      <article id="3700" class="location-listing">
        <a class="location-title" href="https://discord.gg/TggYZCYkuC">
          Crow
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="Crow.png"
              alt="Crow"
            />
          </div>
        </div>
      </article>

      <article id="5" class="location-listing">
        <a class="location-title" href="https://discord.gg/TggYZCYkuC">
          Kyojiwa
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="Kyojiwa.png"
              alt="Kyojiwa"
            />
          </div>
        </div>
      </article>

      <article id="6" class="location-listing">
        <a
          class="location-title"
          href="https://www.youtube.com/channel/UCX01iwhHZ3RNCpSR_F3r8xA"
        >
          TheElkmenArrive
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="TheElkmenArrive.png"
              alt="TheElkmenArrive"
            />
          </div>
        </div>
      </article>

      <article id="7" class="location-listing">
        <a
          class="location-title"
          href="https://www.youtube.com/channel/UCggFFMWTkVrTTL3Hs-4K5Bg"
        >
          Fregaunt
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="Fregaunt.png"
              alt="Fregaunt"
            />
          </div>
        </div>
      </article>

      <article id="8" class="location-listing">
        <a
          class="location-title"
          href="https://www.youtube.com/channel/UCjO8xEExIIEjBGGW8AFgT1Q"
        >
          MicToProGamer
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="MicToProGamer.png"
              alt="MicToProGamer"
            />
          </div>
        </div>
      </article>
      
       <article id="78" class="location-listing">
        <a
          class="location-title"
          href="https://discord.gg/TggYZCYkuC"
        >
          Ikol
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src=   "Ikol.png"
              alt="Ikol"
            />
          </div>
        </div>
      </article>
      <article id="69420" class="location-listing">
        <a
          class="location-title"
          href="https://discord.gg/TggYZCYkuC"
        >
          Hot Choclate
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src=   "HotChoclate.png"
              alt="Hot Choclate"
            />
          </div>
        </div>
      </article>
      <article id="42069" class="location-listing">
        <a
          class="location-title"
          href="https://www.youtube.com/channel/UCOFMPOxqzCpNJ4AltUkRitg/featured"
        >
        J の 7
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src=   "ManTheGerman.png"
              alt="J の 7"
            />
          </div>
        </div>
      </article>
      
    </div>
    <!-- end grid container -->

    <h1
      style="
        margin-top: 10%;
        margin-bottom: 5%;
        align-items: center;
        justify-content: center;
      "
      id="Games"
    >
      Projects
    </h1>
     <div class="grid-container2">
      <article id="36385" class="location-listing">
        <a
          class="location-title"
          href="/Orchard"

        >
          ORCHARD
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="Orchard.png"
              alt="ORCHARD"
            />
          </div>
        </div>
      </article>

      <article id="3288" class="location-listing">
        <a
          class="location-title"
          href="/StickmanSandbox"
        >
          Stickman Sandbox
        </a>

        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="StickmanSandbox.png"
              alt="Stickman Sandbox"
            />
          </div>
        </div>
      </article>
   
    </div>
    <div class="grid-container3">
      <article id="3069" class="location-listing">
        <a
          class="location-title"
          href="/BuildScript"
        >
          Build Script
        </a>
        <br>
        <div class="location-image">
          <div>
            <img
              width="200"
              height="200"
              src="BuildScript.png"
              alt="Build Script Logo"
            />
          </div>
        </div>
      </article>
   
    </div>
    <!-- end grid container -->
<p id="About-Us">
⠀
    </p>       <h1
      style="
        margin-top: 5%;
        align-items: center;
        justify-content: center;
      "
      id="AB2"
           >About Us</h1>
    
             <h2
      style="
        align-items: center;
        justify-content: center;
        width: 1;
         
        
      "

           >We are a small group of Programmers, Muscisians, and Artists, that love making video games!</h2>
      <br>
      <section id="Contact"></section>
       <h1  style="
        margin-top: 10%;
        align-items: center;
        justify-content: center;
      "
      id="C1"
     
           >How can you get in contact?</h1>
    <h2 style="
        align-items: center;
        justify-content: center;
      ">
      You can reach us at our discord server or our email. You may not receive an immediate response when messaging our email, but we our active in our discord quite often!
    </h2>
          <h3 style="
            margin-top: 1%;
            align-items: center;
            justify-content: center;
            font-size: 2rem;" id="Contact2">
          Email: ohminteractiveofficial@gmail.com 
          </h3>
          <a href="https://discord.gg/TggYZCYkuC" class="disbutton" style="font-size: 2rem;">Discord</a>

<p id="JTT">
⠀
    </p>       <h1
      style="
        margin-top: 10%;
        align-items: center;
        justify-content: center;
      "
      id="JT2"
           >Join the Team</h1>
    
             <h2
      style="
        align-items: center;
        justify-content: center;
        width: 1;
         
        
      "

           >If you would like to Join the Team, simply dm Omegaadev on discord with some of your work, or send an email with the same contents. You can find our contact information <a class="disbutton" href="#Contact">here</a>. Can't wait to see your submissions!</h2>
</div>
{/if}