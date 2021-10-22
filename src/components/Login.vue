<template>
  <div>
    <header class="banner">
      <img>       
    </header>
    <nav
      class="navbar navbar-expand-lg navbar-light sticky-top"
      style="background-color: #92cfe6"
    >
      <div class="container-fluid">
        <a class="navbar-brand" href="index.html">{{marca}}</a>
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
            <li class="nav-item" >
                            <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Productos</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link">Mantenimiento</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link">Contacto</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link">Pedidos</a>
                        </li>
          </ul>
          <form class="d-flex">
            <!-- <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search"> -->
            <!-- <button class="btn btn-outline-primary" type="submit">Cerrar Sesión</button> -->
            <li class="nav-item dropdown" style="list-style: none">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                style="color: rgba(0, 0, 0, 0.9)"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                {{user.nombre+" "+user.apellido}}
                <i
                  class="fa fa-user"
                  aria-hidden="false"
                  style="padding-left: 10px"
                ></i>
              </a>

              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Perfil</a></li>
                <li>
                  <hr class="dropdown-divider" />
                </li>
                <li><a class="dropdown-item" href="#">Cerrar sesión</a></li>
              </ul>
            </li>
          </form>
        </div>
      </div>
    </nav>
    <div class="login">   
        <form class="container">
      <h3>Inicio de Sesión</h3>
      <div class="row form">        
        <div class="mb-3 lbl">
          <label for="exampleInputEmail1" class="form-label">Correo</label>
          <input
            type="email"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
          />
        </div>
        <div class="mb-3 lbl">
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
        <button type="submit" class="btn btn-primary">Ingresar</button>
      </div>
    </form>
            <footer class="mt-3" style="border-top: 1px solid #e0e0ef;">
                <h6 style="padding: 30px;  font-size: calc(0.8125rem - 0.05rem); color: #6c757d;">Copyrigth &#9400 2021. Todos los derechos reservados</h6>
            </footer>
        
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        nombre: "Miguel",
        apellido: "Mendez",
      },
      marca: "BikeLatamShop",
      menu: [
        { title: "Inicio" + "<h1>hola</h1>" },
        { title: "Inicio1" + "<h1>hola</h1>" },
        { title: "Inicio2" + "<h1>hola</h1>" },
        { title: "Inicio3" + "<h1>hola</h1>" },
      ],
    };
  },
};
</script>


<style>
/* header {
    height: 100vh;
    background-image: url(../assets/img/mantenimiento/bannerMT.png);
} */

.banner {
  background-size: cover;
  background-image: url(../assets/img/mantenimiento/bannerMT.png);
}

img {
  height: 181px;
}

.container {
  width: 500px;
  /* border: 1px solid red; */
  padding: 20px;
  background: #f2f2f2;
  border-radius: 5px;
}

.form {
  padding: 0px 20px;
}

.btn-enviar {
  text-align: right;
  margin: 0 15px;
}

.btn {
  width: 160px;
  margin: 5px;
}

.form-label {
  padding-left: 8px;
}

.lbl {
  text-align: left;
}

.login {
  padding: 30px;
}

.navbar-nav{
  margin-left: 250px;
}

.nav-item{
    padding-right: 10px;
}

</style>