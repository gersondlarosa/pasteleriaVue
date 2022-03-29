<template >
<h1>Sugerencias</h1>
  <div class="container item3">
    <div class="row">
      <div class="col-3">
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" src="../assets/oreja.jpg" alt="Card image cap">
          <div class="card-body">
            <p class="card-text">Oreja $9.00</p>
          </div>
          </div>
      </div>
      <div class="col-3">
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" src="../assets/chocolatin.jpg" alt="Card image cap">
          <div class="card-body">
            <p class="card-text" style="text-a">Chocolatin $16.00</p>
          </div>
          </div>
      </div>
      <div class="col-3">
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" src="../assets/bisquet.jpg" alt="Card image cap">
          <div class="card-body">
            <p class="card-text">Bisquet $9.00</p>
        </div>
      </div>


       </div>
      <div class="col-3">
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" src="../assets/rebanada.jpg" alt="Card image cap">
          <div class="card-body">
            <p class="card-text">Rebanada $9.00</p>
          </div>
          </div>
       </div>
    </div>
  </div>

</template>

<script>
export default {
  name:'Card'
}
</script>

<style >



h1{
  text-align: center;
  padding-top: .5em;
  padding-bottom: .5em;

}

.item3{
  padding-bottom: 2.5em;
}
p{
  text-align: center;
}
</style>
