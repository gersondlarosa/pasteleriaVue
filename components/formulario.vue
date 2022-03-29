<template>
<h1>Pasteles disponibles disponibles</h1>

<div class="container">
  <div class="row">
    <div class="col-3">
        <form >
          <div class="form-group">
            <label for="exampleFormControlInput1">Chocolate</label>
            <img src="../assets/chocolate.png" class="itemc">
            <input type="text" class="form-control" id="" placeholder="Disponibles 20">
          </div>
          <div class="form-group">
            <label for="exampleFormControlInput1">Tres leches</label>
            <img src="../assets/oreo.png" class="itemc">
            <input type="text" class="form-control" id="" placeholder="Disponibles 20">
          </div>
        </form>

    </div>
    <div class="col-3 oreo">
      <form >
        <div class="form-group">
          <label for="exampleFormControlInput1" class="itemo">Galleta Oreo</label>
          <img src="../assets/chocolate.png" class="itemc">
          <input type="text" class="form-control" id="" placeholder="Disponibles 20">
        </div>
        <div class="form-group">
          <label for="exampleFormControlInput1">Cajeta</label>
          <img src="../assets/oreo.png" class="itemc">
          <input type="text" class="form-control" id="" placeholder="Disponibles 20">
        </div>

      </form>
    </div>
    <div class="col-3">
      <form >
        <div class="form-group">
          <label for="exampleFormControlInput1">Helado</label>
          <img src="../assets/chocolate.png" class="itemc">
          <input type="text" class="form-control" id="" placeholder="Disponibles 20">
        </div>
        <div class="form-group">
          <label for="exampleFormControlInput1">Vainilla</label>
          <img src="../assets/oreo.png" class="itemc">
          <input type="text" class="form-control" id="" placeholder="Disponibles 20">
        </div>

      </form>
    </div>
    <div class="col-3">
      <form >
        <div class="form-group">
          <label for="exampleFormControlInput1">Durazno</label>
          <img src="../assets/chocolate.png" class="itemc">
          <input type="text" class="form-control" id="" placeholder="Disponibles 20">
        </div>
        <div class="form-group">
          <label for="exampleFormControlInput1">Tempura</label>
          <img src="../assets/oreo.png" class="itemc">
          <input type="text" class="form-control" id="" placeholder="Disponibles 20">
        </div>

      </form>
    </div>

  </div>
  <button type="button" class="btn btn-success">Hacer pedido</button>
</div>

</template>

<script>
export default {
  name: 'Formulario',
}
</script>

<style >
.container{
  text-align: center;
  padding-bottom: 3em;
}

.itemc{
  max-width: 10em;
  max-width: 10em;

}

.container .oreo .itemo{
  max-width: 10em;
  max-width: 10em;
}
</style>
