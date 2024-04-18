<template>
  <div id="app" class="container mt-5">
    <h1>IDSHop</h1>
    <p class="animated fadeInRight">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus soluta aliquam voluptatum. Sit sunt voluptate hic cumque, ipsum iure obcaecati molestias adipisci. Illum provident, ratione tenetur tempora expedita autem maiores.</p>
    <font-awesome-icon icon="shopping-cart"></font-awesome-icon>
  </div>
</template>

<script>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';

export default {
  name: "App",
  components: {
    FontAwesomeIcon,
    Price
  }
};
</script>