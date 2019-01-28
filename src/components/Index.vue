<template>
  <main>
    <section id="container">
      <section class="text">
        <p>Plus de 30 ans après la bataille d'Endor, la galaxie n'en a pas fini avec la tyrannie et l’oppression. Les membres de l'Alliance rebelle, devenus la « Résistance », combattent les vestiges de l'Empire réunis sous la bannière du « Premier Ordre ».
          <br>
          <br>Un mystérieux guerrier, Kylo Ren, semble vouer un culte à Dark Vador et pourchasse les ennemis du Premier Ordre à travers la galaxie. Au même moment, une jeune femme nommée Rey, pilleuse d'épaves sur la planète désertique Jakku, va faire la rencontre de Finn, un Stormtrooper en fuite, une rencontre qui bouleversera sa vie.
          <br>
          <br>Plus de 30 ans après la bataille d'Endor, la galaxie n'en a pas fini avec la tyrannie et l’oppression. Les membres de l'Alliance rebelle, devenus la « Résistance », combattent les vestiges de l'Empire réunis sous la bannière du « Premier Ordre ».
          <br>
          <br>Un mystérieux guerrier, Kylo Ren, semble vouer un culte à Dark Vador et pourchasse les ennemis du Premier Ordre à travers la galaxie. Au même moment, une jeune femme nommée Rey, pilleuse d'épaves sur la planète désertique Jakku, va faire la rencontre de Finn, un Stormtrooper en fuite, une rencontre qui bouleversera sa vie.
          <br>
          <br>Plus de 30 ans après la bataille d'Endor, la galaxie n'en a pas fini avec la tyrannie et l’oppression. Les membres de l'Alliance rebelle, devenus la « Résistance », combattent les vestiges de l'Empire réunis sous la bannière du « Premier Ordre ».
          <br>
          <br>Un mystérieux guerrier, Kylo Ren, semble vouer un culte à Dark Vador et pourchasse les ennemis du Premier Ordre à travers la galaxie. Au même moment, une jeune femme nommée Rey, pilleuse d'épaves sur la planète désertique Jakku, va faire la rencontre de Finn, un Stormtrooper en fuite, une rencontre qui bouleversera sa vie.
        </p>
      </section>
      <figure class="image"></figure>
    </section>

    <header class="header-mid"></header>
    <section id="lore-container">
      <h1>A long time ago, in a galaxy far, far away…</h1>
      <section class="img-txt">
        <figure class="img"></figure>
        <p>
          La Guerre des étoiles (titre original Star Wars, soit littéralement Guerres Stellaires ) est une épopée cinématographique de science-fiction créée par George Lucas, considérée comme un élément phare du space opera. Prévue à la base pour être une suite de trois trilogies (triptyque), Lucas fut contraint, par manque de moyens techniques, de commencer par la seconde trilogie (l'Épisode IV - Un nouvel espoir) en 1977. La série connut un succès phénoménal partout dans le monde et engendra une très importante communauté de fans.
          Sans prétendre expliquer le succès du premier film (s'il y avait une recette, cela se saurait), on peut, toutefois, noter que, malgré le manque de moyens (le budget était relativement modeste, les acteurs presque inconnus) :
        </p>
      </section>
      <p>- Il fait appel à des références connues et appréciées des jeunes de l'époque : films de cape et d'épée, westerns, péplums, contes de fées et même le Seigneur des Anneaux de J.R.R. Tolkien ; cette œuvre n'apparaît pas comme de la science-fiction au sens strict mais plutôt comme du space fantasy.
        <br>- Les effets spéciaux, supervisés par Ken Ralston, étaient réellement novateurs, avec notamment la participation de John Dykstra (qui a également participé au premier film de Star Trek), qui avait développé une nouvelle manière d'animer les maquettes des vaisseaux en coordonnant leurs mouvements par ordinateur (Dykstraflex).
        <br>- Le film a développé un univers cohérent, avec, comme préoccupation constante, autant la création d'une ambiance que l'action proprement dite.
        <br>- La musique, composée par John Williams, introduit des thèmes récurrents et des leitmotivs (procédé classique mais renforçant la cohérence).
        <br>
      </p>
    </section>
    <section class="stormtroopers-img"></section>
    <footer id="footer">
      <p class="copyright">TM Lucasfilm Ltd. All Rights Reserved.</p>

      <nav class="footer-nav">
        <ul>
          <li>
            <router-link to="/">Terms of Use</router-link>
          </li>
          <li>
            <router-link to="/">Legal Notices</router-link>
          </li>
          <li>
            <router-link to="/">Privacy Policy</router-link>
          </li>
        </ul>

        <ul>
          <li>
            <router-link to="/">Your California Privacy Rights</router-link>
          </li>
          <li>
            <router-link to="/">Star Wars at Disney Store</router-link>
          </li>
          <li>
            <router-link to="/">Privacy Policy</router-link>
          </li>
        </ul>
        <ul class="follow-us">
          <li>
            <router-link to="/"></router-link>
          </li>
          <li>
            <router-link to="/"></router-link>
          </li>
          <li>
            <router-link to="/"></router-link>
          </li>
        </ul>
      </nav>
    </footer>
  </main>
</template>

<script>
export default {
  name: "Index"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#container {
  padding: 6.5% 5.4% 6.5% 5.4%;
  display: flex;
  justify-content: space-around;
}

@media screen and (max-width: 768px) {
  #container {
    padding: 1%;
    flex-direction: column;
    align-items: center;
  }
  .text {
    font-size: 25px;
    width: 80% !important;
  }

  .image {
    width: 90% !important;
    background-size: cover;
  }
}

.text {
  width: 50%;
  font-size: 18px;
}

.image {
  width: 30%;
  height: 100vh;
  background-image: url("../assets/ad.jpg");
  background-repeat: no-repeat;
  background-position: fixed;
}

.header-mid {
  width: 100%;
  height: 80vh;
  background-image: url("../assets/kiloren.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

/* lore-container */
#lore-container {
  padding: 6.5% 5.4% 6.5% 5.4%;
}

#lore-container h1 {
  font-size: 20px;
  text-align: center;
}

#lore-container p {
  font-size: 14px;
}

.img-txt {
  display: flex;
  justify-content: space-between;
}

@media screen and (max-width: 768px) {
  .img-txt {
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
}

.img {
  margin-left: 0;
  width: 30%;
  height: 40vh;
  background-image: url("../assets/r2d2_c3p0.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}

@media screen and (max-width: 768px) {
  .img {
    width: 100%;
  }
}

.img-txt p {
  width: 70%;
}

@media screen and (max-width: 768px) {
  .img-txt p {
    width: 100%;
  }
}

.stormtroopers-img {
  width: 100%;
  height: 50vh;
  background-image: url("../assets/stormtroopers.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
/* FOOTER */

#footer {
  width: 100%;
  height: 50vh;
  background-image: url("../assets/darthvader_2x.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

  display: flex;
  flex-direction: column;
  justify-content: center;
}

#footer .copyright {
  text-align: center;
  color: gray;
  margin: 0;
}

.footer-nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.footer-nav ul {
  list-style: none;
}

.follow-us {
  margin: 0;
  padding: 0;
  width: 33%;
  display: flex;
  justify-content: center;
}

.follow-us li {
  display: block;
  margin-left: 10px;
  width: 30px;
  height: 30px;
  list-style: none;
}

.follow-us li:first-child {
  background-image: url("../assets/icon_facebook.png");
  background-size: contain;
  background-repeat: no-repeat;
}

.follow-us li:nth-child(2) {
  background-image: url("../assets/icon_twitter.png");
  background-size: contain;
  background-repeat: no-repeat;
}

.follow-us li:nth-child(3) {
  background-image: url("../assets/icon_instagram.png");
  background-size: contain;
  background-repeat: no-repeat;
}

#footer li a {
  color: gray;
}
</style>
