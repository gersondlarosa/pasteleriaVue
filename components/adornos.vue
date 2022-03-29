<template >
  <h1>Escoje tus adornos</h1>
  <div class="container">
    <div class="row">
      <div class="col-3">
          <form >
            <div class="form-check">
  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
  <label class="form-check-label" for="exampleRadios1">
    Adorno de chocolate
  </label>
</div>
<div class="form-check">
<input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
<label class="form-check-label" for="exampleRadios1">
Pastillage
</label>
</div>
          </form>
      </div>
      <div class="col-3 oreo">
        <form >
          <div class="form-check">
    <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
    <label class="form-check-label" for="exampleRadios1">
      Muñecos de Marvel y DC
    </label>
  </div>
  <div class="form-check">
  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
  <label class="form-check-label" for="exampleRadios1">
    Muñeco de Boda
  </label>
</div>

        </form>
      </div>
      <div class="col-3">
        <form >
          <div class="form-check">
    <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
    <label class="form-check-label" for="exampleRadios1">
      Copa primera comunion
    </label>
  </div>
  <div class="form-check">
  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
  <label class="form-check-label" for="exampleRadios1">
    Fondad
  </label>
</div>

        </form>
      </div>
      <div class="col-3">
        <form >
          <div class="form-check">
                  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
                  <label class="form-check-label" for="exampleRadios1">
                    Chocolateria
                  </label>
          </div>

          <div class="form-check">
                <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
                <label class="form-check-label" for="exampleRadios1">
                  Muñeco de Bodas
                </label>
          </div>

        </form>
      </div>

    </div>
    <button type="button" class="btn btn-success">Hacer pedido</button>
  </div>
</template>

<script>
export default {
  name: 'Adornos',
}
</script>

<style media="screen">
  h1{
    text-align: center;
  }
</style>
