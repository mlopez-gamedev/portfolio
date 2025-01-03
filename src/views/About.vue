<template>
  <div style="margin-bottom: 80px;">
    <h1>Howdy, friend!</h1>

    <div class="paragraph">
      <div class="paragraph">
        I’m <strong>Miguel López</strong>, a game developer and programmer based in <strong>Sevilla</strong>, passionate about bringing ideas to life. I’m all about Unity, but I don’t just stick to programming or just Unity—I’m involved in every aspect of creating games.
      </div>
      <div style="margin-top: 20px;">
        With <strong>15+ years of experience</strong> in the industry, I got started because I love how games combine art with tech, and let’s be honest—playing them is just incredibly fun!
      </div>
      <div style="margin-top: 20px;">
        I co-founded <a href="https://koronstudios.com">Koron Studios</a>, a game company we built from the ground up, and after 7 years of blood, sweat and pixels, we sold it to explore new challenges (no Forbes article, but I’ll take the pride in everything we accomplished as a team). This journey gave me a ton of invaluable experience and knowledge.
      </div>
      <div style="margin-top: 20px;">
        Now, I'm working at <a href="https://odderslab.com">Odders Lab</a>, diving into the world of Virtual Reality and Mixed Reality for the awesome fitness brand <strong>Les Mills</strong>.
      </div>
      <div style="margin-top: 20px;">
        When I’m not coding, you’ll find me smashing padel balls, soaking up the sun on a terrace with friends, or jumping into a game jam to experiment with fresh ideas and ways to create awesome games.
      </div>
    </div>
    
    <div class="photo">
      <img src="img/avatar.png" alt="Hand drawing of Miguel having a coffee, by Miriam Pérez" title="It's-a-me, Miguel! By Miriam Pérez" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  text-align: center;
}

.photo img {
  height: 320px;
  width: 320px;
  border-radius: 40%;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding-left: 60px;
  }
}

</style>
<script lang="ts">
</script>