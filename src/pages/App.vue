<template>
  <div id="app">
    <navbar />
    <header class="bg-info py-5 mb-5">
    <div class="container h-100">
      <div class="row h-100 align-items-center">
        <div class="col-lg-12">
          <h1 class="display-4 text-white mt-5 mb-2">Evan Smith</h1>
          <p class="lead mb-5 text-white-50">My personal space.</p>
        </div>
      </div>
    </div>
  </header>

  <!-- Page Content -->
  <div class="container">

    <div class="row">
      <div class="col-md-8 mb-5">
        <h2>About me</h2>
        <hr>
        <p></p>
        <p></p>
      </div>
      <div class="col-md-4 mb-5">
        <h2>Contact Me</h2>
        <hr>
        <address>
          <strong>Email</strong>
          <br>
          <a href="mailto:#">smithevandaniel@gmail.com</a>
        </address>
        <address>
          <strong>Phone</strong>
          <br>
          <p>Please reach out to me at the email address above to get my phone number.</p>
        </address>
      </div>
    </div>
    <!-- /.row -->

    <div class="row">
      <div class="col-md-4 mb-5">
        <div class="card h-100">
          <img class="card-img-top" src="" alt="">
          <div class="card-body">
            <h4 class="card-title">Project 1</h4>
            <p class="card-text">description</p>
          </div>
          <div class="card-footer">
            <a href="#" class="btn btn-primary">Check it out</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-5">
        <div class="card h-100">
          <img class="card-img-top" src="" alt="">
          <div class="card-body">
            <h4 class="card-title">Project 2</h4>
            <p class="card-text">description</p>
          </div>
          <div class="card-footer">
            <a href="#" class="btn btn-primary">Check it out</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-5">
        <div class="card h-100">
          <img class="card-img-top" src="" alt="">
          <div class="card-body">
            <h4 class="card-title">Project 3</h4>
            <p class="card-text">description</p>
          </div>
          <div class="card-footer">
            <a href="#" class="btn btn-primary">Check it out</a>
          </div>
        </div>
      </div>
    </div>
    <!-- /.row -->

  </div>
  <!-- /.container -->
  </div>
</template>

<script>
import navbar from '../components/navbar.vue'

export default {
  name: 'App',
  components: {
    navbar
  }
}
</script>

<style>
</style>
