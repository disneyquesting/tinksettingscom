<template>
  <div class="consoleBlocks">
    <div class="console">
      <a href="/settings/sega"
        ><img src="/consoles/sega.png" alt="Sega Family Settings"
      /></a>
    </div>
    <div class="console">
      <a href="/settings/nintendo"
        ><img src="/consoles/nintendo.png" alt="Nintendo Family Settings"
      /></a>
    </div>
    <div class="console">
      <a href="/settings/sony"
        ><img
          src="/consoles/playstation.png"
          alt="Sony PlayStation Family Settings"
      /></a>
    </div>
    <div class="console">
      <a href="/settings/microsoft">
        <img src="/consoles/xbox.png" alt="Microsoft Family Settings" />
      </a>
    </div>
    <div class="console">
      <a href="/settings/snk">
        <img src="/consoles/snk.png" alt="SNK Family Settings"
      /></a>
    </div>
    <div class="console">
      <a href="/settings/hudson">
        <img src="/consoles/pcengine.png" alt="Hudson Family Settings"
      /></a>
    </div>
    <div class="console">
      <a href="/settings/atari">
        <img src="/consoles/atari.png" alt="Atari Family Settings"
      /></a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
img {
  max-width: 200px;
}

.consoleBlocks {
  display: grid;
  grid-template-columns: auto auto auto auto;
  align-content: center;
}

.console {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
