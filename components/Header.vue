<template>
  <nav>
    <div class="siteName">
      <h2>TinkSettings.Com</h2>
    </div>
    <div class="linkBar">
      <ul>
        <li>
          <a href="/">Home</a>
        </li>
        <li>
          <a href="/settings">Console Settings</a>
        </li>
        <li>
          <a href="/submit">Submit Settings</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script></script>

<style>
nav {
  display: grid;
  grid-template-columns: auto auto;
  width: 100%;
  background: white;
  text-align: center;
}

nav .siteName {
  padding-top: 5px;
  padding-bottom: 5px;
}
nav h2 {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 400;
  letter-spacing: 1px;
  margin-top: auto;
  color: #76323f;
}

nav ul {
  padding-top: 5px;
  padding-bottom: 5px;
  list-style: none;
  text-align: center;
}

nav li {
  display: inline;
}

nav li a {
  font-size: 25px;
  margin-left: 25px;
  margin-right: 25px;
  color: #565656;
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
}
</style>
