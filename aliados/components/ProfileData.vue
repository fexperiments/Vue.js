<template>
  <div class="wrapper">
    <div class="profile-wr">
      <h1>
        Jorge Manuel Pineda
      </h1>
      <p class="since-text">
        Aliado desde 2018
      </p>

      <hr></hr>
      <div class="row align-items-end">
        <div class="col-sm">
          <h3>
            Nutipuntos:
          </h3>
        </div>
        <div class="col-sm">
          <h3 class="text-danger">
            562.13
          </h3>
        </div>
        <div class="col-sm text-right">
          <div class="row align-items-end">
            <div class="col-sm">
              ver más
            </div>
            <img class="col-dm ver-mas" src="~/assets/ver-mas.png"></img>
          </div>
        </div>
      </div>

      <hr></hr>
      <div class="row align-items-end">
        <div class="col-sm">
          <h3>
            Referidos:
          </h3>
        </div>
        <div class="col-sm">
          <h3 class="text-success">
            52
          </h3>
        </div>
        <div class="col-sm text-right">
          <div class="row align-items-end">
            <div class="col-sm">
              ver más
            </div>
            <img class="col-dm ver-mas" src="~/assets/ver-mas.png"></img>
          </div>
        </div>
      </div>

      <hr></hr>
      <div class="row align-items-end">
        <div class="col-sm">
          <h5>
            Puntos redimidos:
          </h5>
        </div>
        <div class="col-sm">
          <h5 class="text-warning">
            5690
          </h5>
        </div>
        <div class="col-sm text-right">
          <div class="row align-items-end">
            <div class="col-sm">
              ver más
            </div>
            <img class="col-dm ver-mas" src="~/assets/ver-mas.png"></img>
          </div>
        </div>
      </div>
    </div>
    <div class="buttons row">
      <div class="col-sm">
        <button
          type="button"
          class="btn btn-primary"
          style="width:100%"
        >
          Agregar Referido
        </button>
      </div>
      <div class="col-sm">
        <button
          type="button"
          class="btn btn-warning"
          style="width:100%"
        >
          Redimir Puntos
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  margin: 80px;
}

.since-text {
  margin-bottom: 40px;
}

.ver-mas {
  max-width: 20px;
}

.buttons {
  max-width: 800px;
  margin: 0 auto;
}

.profile-wr {
  max-width: 800px;
  margin: 0 auto;
  background-color: #fff;
  padding: 15px 40px 50px;
  border: 1px solid #5e5e5e5e;
  border-radius: 10px;
  margin-bottom: 20px;
}
</style>
