<!-- TEMPLATE -->

<template>
  <div id="app">
    <h1 class="site-title">{{ title }}</h1>
    <span class="site-description">{{ currentDate }}</span>

    <!-- entry list -->
    <ul class="entry-list">
      <li class="entry-item">
        <span class="entry-daytime">10:15 Uhr</span><br />
        <h3 class="entry-title">Statischer Titel 1</h3>
        <span class="entry-description">Statische Beschreibung 1</span><br />
      </li>
      <li class="entry-item">
        <span class="entry-daytime">10:30 Uhr</span><br />
        <h3 class="entry-title">Statischer Titel 2</h3>
        <span class="entry-description">Statische Beschreibung 2</span><br />
      </li>
    </ul>

    <!-- footer -->
    <footer class="footer">
      <img
        src="src/assets/STZH_SEB_Logo.png"
        alt="Stadt Zürich Soziale Betriebe"
      >
      <img
        src="src/assets/Opportunity.png"
        alt="Opportunity Zürich Logo"
      >
      <img
        src="src/assets/SAG_Logo_De.png"
        alt="Stiftung Arbeitsgestaltung Logo"
      >
    </footer>
  </div>
</template>





<!-- SCRIPT -->
<script>
</script>


<!-- STYLE -->

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@500&display=swap");

body {
  background: #E8EFF4;
}

#app {
  font-family: "Inter", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #323d4a;
  margin: 60px;
}

.site-title {
  font-family: Inter;
  font-size: 62px;
  font-weight: 900;
  line-height: 75px;
  letter-spacing: 0em;
  text-align: left;
  position




</style>
