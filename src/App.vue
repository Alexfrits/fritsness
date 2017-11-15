<template>
  <div id="app">
    <header class="af-header">
      <h1 class="af-title">
        <img class="af-logo" src="/static/img/af-monogram.min.svg" alt="Alexandre Frits monogram" width="240" height="240">
        <span class="af-title__firstname">Alexandre</span>
        <span class="af-title__lastname">Frits</span>
      </h1>
      <div>
        <h2>UI/UX Designer</h2>
        <ul>
          <li>0479230135</li>
          <li>frits.alex@gmail.com</li>
          <li>Route de la Hesbaye 95, 5310 Noville-sur-Mehaigne</li>
          <li>Permis B et véhicule</li>
        </ul>
      </div>
      <a href="http://be.linkedin.com/in/alexandrefrits">/in/alexandrefrits</a>
    </header>
    <ol class="af-timeline">
      <li class="af-timeline__item">naissance</li>
      <li class="af-timeline__item">études</li>
      <li class="af-timeline__item">
        formation Frontend Cepegra Gosselies
        <ol>
          <li>stage HTML - CSS</li>
          <li>Finaliste Skills Belgium catégorie webdesign </li>
          <li>Stage Frontend Tapptic Liège</li>
        </ol>
      </li>
      <li class="af-timeline__item">Freelance Webdesigner</li>
      <li class="af-timeline__item">Group S</li>
    </ol>
    <main>
      <section>
        <h3>Skills</h3>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JS</li>
          <li>Photoshop</li>
          <li>Illustrator</li>
          <li>Figma</li>
        </ul>
      </section>
      <section>
        <h3>Other</h3>
        <ul>
          <li>SCSS</li>
          <li>Rsponsive</li>
          <li>Git</li>
          <li>UI</li>
          <li>UX</li>
          <li>Wireframe</li>
          <li>VueJS</li>
          <li>NPM</li>
        </ul>
      </section>
    </main>
    <aside>
      <section>
        <h3>Langues</h3>
      </section>
      <section>
        <h3>Atouts</h3>
        <ul>
          <li>Autonomie</li>
          <li>Sens des responsabilités</li>
          <li>Bon contact Humain</li>
          <li>Gestion d'équipe</li>
          <li>Travail d'équipe</li>
          <li>Prise de décisions</li>
          <li>Curiosité intellectuelle</li>
          <li>Minutie</li>
          <li>Passion du web</li>
        </ul>
      </section>
      <section>
        <h3>Centres d'intérêts</h3>
        <ul>
          <li>design</li>
          <li>cyclisme</li>
          <li>bricolage</li>
          <li>comics</li>
          <li>jeux vidéo</li>
          <li>Lego</li>
          <li>mécanique</li>
        </ul>
      </section>
    </aside>
  </div>
</template>

<style src="./styles/main.scss" lang="scss"></style>

<script>

export default {
  name: 'app',
  components: {

  }
}
</script>