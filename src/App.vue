<template>
  <div id="app main-wrap">
    <Navigation/>
    <Banner/>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue';
import Banner from './components/Banner.vue';

export default {
  name: 'App',
  components: {
    Navigation,
    Banner,
  }
}
</script>

<style>
@import url(https://fonts.googleapis.com/css?family=Roboto+Condensed:300,400,700);
html, body {
    height: 100%;
    position:  relative;
}

body {
    font-family: 'Roboto Condensed', sans-serif;
    color: #424242;
    font-size: 16px;
    overflow: hidden;
}

a:hover, a:focus {
    text-decoration: none;
}

input:focus, textarea:focus, button:focus, a:focus {
    outline: none;
}

button[type=submit], input[type=submit] {
    cursor: pointer;
}

ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

h1, h2, h3, h4 {
    font-weight: 700;
    color: #1F4559;
    margin: 0 0 10px;
}

img {
    max-width: 100%;
}

input, textarea {
    padding: 10px 15px;
    margin-bottom: 1em;
}

.bg {
    -webkit-background-size: cover;
    background-size: cover;
    background-position: center center;
    background-color: #ddd;
    background-repeat: no-repeat;
}

.myPort-btn {
    display: inline-block;
    padding: 15px 30px;
    text-align: center;
    -moz-transition: all 0.3s ease;
    -o-transition: all 0.3s ease;
    -ms-transition: all 0.3s ease;
    -webkit-transition: all 0.3s ease;
    transition: all 0.3s ease;
    border: 1px solid;
    color: #fff;
    letter-spacing: 0.2rem;
    text-transform: capitalize;
    font-weight: normal;
    margin-right: 30px;
}

.myPort-btn:hover {
    color: #fff;
    background-color: #1F4559;
    border-color: #1F4559;
}

.boxed-btn {
    background-color: #00d0e5;
    border-color: #00d0e5;
}

.transparent-btn {
    color: #00d0e5;
    border-color: #00d0e5;
}
</style>
