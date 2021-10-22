<template>
  <div>
    <header class="banner">
      <img />
    </header>

    <!-- <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Dropdown
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled">Disabled</a>
            </li>
          </ul>
          <form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <button class="btn btn-outline-success" type="submit">
              Search
            </button>
          </form>
        </div>
      </div>
    </nav> -->
    <form class="container">
      <h3>Registro</h3>
      <div class="row form">
        <div class="mb-3 lbl col-sm-6">
          <label for="exampleInputEmail1" class="form-label">Nombres</label>
          <input
            type="text"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
          />
        </div>
        <div class="mb-3 lbl col-sm-6">
          <label for="exampleInputEmail1" class="form-label">Apellidos</label>
          <input
            type="text"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
          />
        </div>
        <div class="mb-3 lbl col-sm-6">
          <label for="exampleInputEmail1" class="form-label">Correo</label>
          <input
            type="email"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
          />
        </div>
        <div class="mb-3 lbl col-sm-6">
          <label for="exampleInputEmail1" class="form-label">Telefono</label>
          <input
            type="text"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
          />
        </div>
      </div>
      <div class="btn-enviar">
        <button type="submit" class="btn btn-secondary">Cancelar</button>
        <button type="submit" class="btn btn-primary">Enviar</button>
      </div>
    </form>
  </div>
</template>

<style>
.container {
  width: 700px;
  /* border: 1px solid red; */
  padding: 30px;
  background: #f2f2f2;
  border-radius: 5px;
}

.form {
  padding-top: 20px;
}

.btn-enviar {
  text-align: right;
  padding-top: 15px;
}

.btn {
  width: 140px;
  margin: 5px;
}

.form-label {
  padding-left: 8px;
}

.lbl {
  text-align: left;
}

/* img{
    height: 181px;
}

.banner {

    background-size: cover;
    background-image: url(../assets/img/mantenimiento/bannerMT.png);
} */

</style>