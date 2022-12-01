<script>
  import {page} from '$app/stores'
  console.log($page.routeId)
</script>
{#if $page.routeId === "/Orchard" || $page.routeId === "/StickmanSandbox" || $page.routeId == "/BuildScript"}
<div class="ownernav">
  <nav class="navbar">
    <!-- LOGO -->
    <div class="logo">
      <a href="/">
      <img
        src="OhmLogo.png"
        alt="Ohm"
        style="width: 50px; height: 50px"

      />
      </a>
    </div>
    <div class="navbar-alt">
    <!-- NAVIGATION MENU -->
    <ul style="list-style: none" class="nav-links">
      <!-- USING CHECKBOX HACK -->

      <!-- NAVIGATION MENUS -->
      <div class="menu">
        <li><a href="/">Home</a></li>
        
        <li class="services">
          <a href="{$page.routeId}">Projects</a>
          <!-- DROPDOWN MENU -->
          <ul class="dropdown" style="list-style: none">
            <li> <a href="/Orchard">ORCHARD</a> </li>
            <li><a href="/StickmanSandbox">Stickman Sandbox</a></li>
            <li><a href="/BuildScript">Build Script</a></li>
          </ul>
        </li>
      </div>
    </ul>
  </div>

  </nav>
</div>
{:else}
<div class="ownernav">
  <nav class="navbar">
    <!-- LOGO -->
    <div class="logo">
      <a href="#Home">
      <img
        src="OhmLogo.png"
        alt="Ohm"
        style="width: 50px; height: 50px"

      />
      </a>
    </div>
    <!-- NAVIGATION MENU -->
    <ul style="list-style: none" class="nav-links">
      <!-- USING CHECKBOX HACK -->

      <!-- NAVIGATION MENUS -->
      <div class="menu">
        <li><a href="/">Home</a></li>
        
        <li class="services">
          <a href="#Games">Projects</a>
          <!-- DROPDOWN MENU -->
          <ul class="dropdown" style="list-style: none">
            <li> <a href="/Orchard">ORCHARD</a> </li>
            <li><a href="/StickmanSandbox">Stickman Sandbox</a></li>
            <li><a href="/BuildScript">Build Script</a></li>
          </ul>
        </li>
        <li><a href="#About-Us">About</a></li>
        
        <li><a href="#Contact">Contact Us</a></li>
        <li><a href="#JTT">Join the Team</a></li>
      </div>
    </ul>

  </nav>
</div>
{/if}
<style>
  .logo{
    z-index: 999;
  }
</style>