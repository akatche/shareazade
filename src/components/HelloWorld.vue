<template>
  <section class="hero is-success is-fullheight">
    <div class="hero-body">
      <div class="container has-text-centered">
        <div class="column is-6 is-offset-3 has-text-centered">
            <figure class="image is-2by1">
              <img src="https://dummyimage.com/640x320/000/fff.png">
            </figure>
            <h1 class="title">
              Watch YouTube videos with your friends
            </h1>
            <h2 class="subtitle">
              Shareazade lets your interact with your friends on a private chat room while watching YouTube videos at the same time
            </h2>
            <div class="box">
                <div class="field is-grouped">
                    <p class="control is-expanded">
                        <input class="input" type="text" placeholder="Enter your email">
                    </p>
                    <p class="control">
                        <a class="button is-info">
                          Watch It  
                        </a>
                    </p>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>