<script>
    import 'bootstrap/dist/css/bootstrap.min.css';
</script>

<nav class="navbar bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand text-white" href="/">ACM Auth</a>
      <a class="nav-link text-white" href="/">Home</a>
      <a class="nav-link text-white" href="/about">About Us</a>
      <a class="nav-link text-white" href="/events">Events</a>
      <a class="nav-link text-white" href="/projects">Projects</a>
      <a class="nav-link text-white" href="/members">Members</a>
      <a class="nav-link text-white" href="/">Join Us</a>
    </div>
  </nav>
  
  <div style="padding-top: 80px;">
    <slot />
  </div>
  