<template>
  <nav class="navbar navbar-dark bg-dark">
    <h3 class="text-light">ES</h3>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-item nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
        <a class="nav-item nav-link" href="#">About Me</a>
        <a class="nav-item nav-link" href="#">Projects</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      skills: [
        { "skill": "Vue.js"},
        { "skill": "Frontend Developer"}
      ]
    }
  }
}
</script>

<style>
</style>
