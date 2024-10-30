<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="red">{{ msg }}</h1>
    <h3>
      I dunno what we're doing exactly so I guess I'll just share some factoids with you all.
    </h3>
  </div>
  <main>
    <TheWelcome />
    {{ edit_1 }} <!-- Added new div -->
    <div class="small-text">I don't know why there's an image of a bomb here to be honest. But don't worry, this bomb was AI-generated. So it will not hurt you.</div>
    {{ edit_1 }} <!-- End of new div -->
  </main>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}

.small-text { /* New class for smaller text */
  font-size: 0.5rem; /* Adjust the size as needed */
}
</style>
