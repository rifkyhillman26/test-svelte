<script>
  $(".dropdown-trigger").dropdown();
</script>

<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css" />

<nav>
  <div class="nav-wrapper">
    <a class="dropdown-trigger btn" href="#" data-target="dropdown1">
      Drop Me!
    </a>

    <!-- Dropdown Structure -->
    <ul id="dropdown1" class="dropdown-content">
      <li>
        <a href="#!">one</a>
      </li>
      <li>
        <a href="#!">two</a>
      </li>
      <li class="divider" tabindex="-1" />
      <li>
        <a href="#!">three</a>
      </li>
      <li>
        <a href="#!">
          <i class="material-icons">view_module</i>
          four
        </a>
      </li>
      <li>
        <a href="#!">
          <i class="material-icons">cloud</i>
          five
        </a>
      </li>
    </ul>
  </div>
</nav>
