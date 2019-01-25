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
    </section>
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
</style>
