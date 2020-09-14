<template>
  <div>
    <div class="thread">
      <div>
        <p>
          <a href="#">{{thread.title}}</a>
        </p>
        <p class="text-faded text-xsmall">
          By
          <a href="#">Joseph Kerr</a>
          , {{thread.publishedAt}}.
        </p>
      </div>

      <div>
        <p>
          <a href="thread.html">Which is your favorite carbohydrate? 🤓</a>
        </p>
        <p class="text-faded text-xsmall">
          By
          <a href="profile.html">Ray-Nathan James</a>, 1 month ago
        </p>
      </div>

      <div class="activity">
        <p class="replies-count">0 replies</p>

        <img
          class="avatar-medium"
          src="http://i0.kym-cdn.com/photos/images/facebook/000/010/934/46623-batman_pikachu_super.png"
          alt
        />

        <!-- <div>
          <p class="text-xsmall">
            <a href="#">Bruce Wayne</a>
          </p>
          <p class="text-xsamll text-faded">2 hours ago</p>
        </div>-->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    thread: {
      required: true,
      type: Object,
    },
  },
};
</script>

<style>
</style>
