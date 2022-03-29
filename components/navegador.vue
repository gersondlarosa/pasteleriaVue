<template >
  <nav class="navbar navbar-expand-lg navbar-light  item">
    <img src="../assets/queremos_pastel.png" width="80" height="70" alt="">

  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link pasteleria" href="#" style="color: #ffff;">Queremos pastel <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#" style="color: #ffff;">Usuarios</a>
      </li>

      <li class="nav-item">
          <router-link to="/pedidos" class="nav-link" href="#" style="color: #ffff;">Pasteleria</router-link>
      </li>
    </ul>

  </div>
</nav>


</template>

<script>
export default {
  name: 'Navegador',
}
</script>

<style >
    .item{
      background-color: rgb(0 123 255 / 46%);;
    }



</style>
