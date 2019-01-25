<template>
  <main>
    <section id="container">
      <section class="text">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Obcaecati, hic earum similique fuga itaque saepe porro placeat totam dignissimos nam nisi aliquam, doloremque consequuntur iure laboriosam impedit facere accusantium voluptate ullam error? Nostrum pariatur praesentium ab voluptate nulla quia facilis corporis! Porro cum rerum doloribus labore, at iusto distinctio fugit reprehenderit quibusdam asperiores, voluptate laudantium eius? Aspernatur quis quos aperiam veniam obcaecati iure alias vitae. Aliquam eligendi voluptates natus quod eaque excepturi harum quos corporis sapiente, perspiciatis obcaecati debitis error. Necessitatibus corrupti beatae culpa, maiores obcaecati ipsum ullam saepe laudantium modi ratione inventore quod, dolores quisquam. Placeat labore hic perferendis cum facilis deserunt optio? Libero, alias corporis. Dolorem iure ratione, dolor a itaque eveniet aliquid suscipit sunt excepturi beatae impedit, cupiditate eum tempora officia? Delectus repellendus cupiditate repudiandae error at vero laborum tempore, placeat sequi magnam saepe, adipisci cum veritatis obcaecati expedita soluta voluptatem debitis sint! Itaque rerum minus debitis laborum corporis recusandae odit repellat eaque, et iure tempora qui rem culpa placeat natus ipsa quia facere exercitationem dignissimos aspernatur nesciunt? Porro earum aut cupiditate explicabo aliquam provident eveniet ipsa deserunt aliquid sequi, voluptas iste fugit similique voluptatibus dignissimos ut esse culpa, nihil sint debitis cumque error, quidem libero velit. Aspernatur cumque neque labore corrupti harum minus nobis facilis omnis molestias. Repudiandae cumque, voluptas praesentium non ea quam illo, nesciunt corrupti amet ad consequatur quaerat nam vel minus soluta odio repellat deleniti quos distinctio sunt ipsam quo iusto quia nulla. Natus ullam corrupti dolor quo tempore optio enim, odio recusandae, minima quas, ipsam aliquam. Error amet corrupti officiis exercitationem nulla accusamus asperiores ex fugit impedit autem. Corporis modi nisi atque fugit nemo error repellendus. Ad asperiores dolor, facere quia deserunt ex voluptate praesentium at, repellat omnis dolorem voluptas impedit nemo sunt amet, eveniet sapiente vero beatae fuga cum. Ratione, eos.</p>
      </section>
      <figure class="image"></figure>
    </section>

    <header class="header-mid"></header>
    <section id="lore-container">
      <h1>A long time ago, in a galaxy far, far away…</h1>
      <section class="img-txt">
        <figure class="img"></figure>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cum harum iste nihil laudantium. Quibusdam optio nostrum beatae? Aspernatur consectetur assumenda officia consequuntur quia quas eaque sit, beatae accusamus facilis ipsa labore repellendus repudiandae deleniti fuga nisi quaerat, nulla magnam necessitatibus culpa commodi perspiciatis. Sed commodi enim dolores asperiores, quidem maxime dolorum aspernatur temporibus numquam voluptate quam animi, qui incidunt architecto magni sunt tenetur minima nemo nulla culpa accusamus perspiciatis? Distinctio asperiores minus, minima harum aspernatur quibusdam dignissimos provident vero consequatur commodi qui illo libero accusamus laboriosam blanditiis facere a nostrum totam, labore sequi non. Saepe vel totam eum quibusdam. Vitae.</p>
      </section>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quae vel ab sapiente, consequuntur unde, cupiditate tempora dignissimos assumenda eum obcaecati repellat, officiis eligendi aliquid minima dolor molestias nostrum corporis. Illum explicabo, hic, maiores quae vel rem vitae a accusantium quidem labore corporis ex? Quod, eaque iste. Quas sint dolor quisquam id labore totam vel blanditiis incidunt soluta laboriosam sit inventore minima earum itaque consectetur, reprehenderit, harum provident dolore quasi ipsa saepe delectus, eos facilis architecto. Asperiores, earum ab, repudiandae fugiat veritatis deleniti labore et veniam, recusandae autem nesciunt. Officiis possimus magnam beatae similique est inventore optio, fugit quidem officia corporis quo perferendis ullam atque obcaecati libero magni tempore? Ad possimus et corrupti officiis, distinctio ipsam. Illum magni quae nihil quod, maiores unde dolorum qui obcaecati vero, hic iusto! Obcaecati doloremque laboriosam, tempora eos eligendi nisi ex consequatur temporibus explicabo, exercitationem, dolorum expedita sint distinctio ipsam. Repellendus eveniet non vitae in, impedit beatae deserunt obcaecati sequi assumenda ut, aliquid adipisci necessitatibus vero minima rem nobis eos earum ad fugiat corrupti culpa quibusdam? Quod distinctio architecto eius quisquam dicta in quos maxime. Perferendis iste, explicabo aliquid necessitatibus temporibus, odit optio, qui eligendi maxime pariatur voluptate fuga! Repellendus deserunt expedita quisquam ratione explicabo?</p>
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
  padding: 10%;
  display: flex;
  justify-content: space-around;
}

.text {
  width: 50%;
}

.image {
  width: 30%;
  height: 100vh;
  background: red;
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
  padding: 10%;
}

#lore-container h1 {
  font-size: 20px;
  text-align: center;
}

.img-txt {
  display: flex;
  justify-content: space-between;
}

.img {
  width: 30%;
  height: 40vh;
  background: red;
}

.img-txt p {
  width: 70%;
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
