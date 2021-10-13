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
            <!-- <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link disabled">Disabled</a>
                        </li> -->
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
    <div class="row" style=" margin: 0;">
        <aside class="col-md-3 mt-5">

            <ul style="list-style: none;">
                <li>
                    <a href="index.html" style="text-decoration: none;">
                        <i class="fa fa-home" aria-hidden="true"></i>
                        <span class="menu-title">Inicio</span>
                    </a>
                </li>
                <li>
                    <a href="productos.html" style="text-decoration: none;">
                        <i class="fa fa-bicycle" aria-hidden="true"></i>
                        <span class="menu-title">Productos</span>
                    </a>
                </li>
                <li>
                    <a href="pedido.html" style="text-decoration: none;">
                        <i class="fa fa-archive" aria-hidden="true"></i>
                        <span class="menu-title">Pedido</span>
                    </a>
                </li>
                <li>
                    <a href="#" style="text-decoration: none;">
                        <i class="fa fa-wrench" aria-hidden="true"></i>
                        <span class="menu-title">Mantenimiento</span>
                    </a>
                </li>
                <li>
                    <a href="contacto.html" style="text-decoration: none;">
                        <i class="fa fa-user" aria-hidden="true"></i>
                        <span class="menu-title">Contacto</span>
                    </a>
                </li>
            </ul>

            


        </aside>
        <main class="col-md-9" style="background:#f2f2f2; padding: 0;">
            <div class="" style=" padding: 40px;">
    
                <div class="col-md-12" style="padding: 10px;">
                    <h1 class="">Mantenimiento</h1>
                </div>
                <div class="row row-cols-1 row-cols-md-3 g-4 mt-1">
                    <div class="col">
                        <div class="card h-100">
                            <img src="https://tuvalum.com/blog/wp-content/uploads/2017/07/revisi%C3%B3n-frenos-disco-bicicleta.jpg"
                                class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Freno de disco</h5>
                                <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                    additional content. This content is a little bit longer.</p>
                            </div>
                            <div class="card-footer">
                                <small class="text-muted">Last updated 3 mins ago</small>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card h-100">
                            <img src="https://www.mtbpro.es/sites/default/files/mtb-pro-mantenimiento_07_mhs17_img_7872.jpg"
                                class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Suspensión</h5>
                                <p class="card-text">This card has supporting text below as a natural lead-in to additional
                                    content.</p>
                            </div>
                            <div class="card-footer">
                                <small class="text-muted">Last updated 3 mins ago</small>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card h-100">
                            <img src="https://www.mtbpro.es/sites/default/files/mtb-pro-mantenimiento_06_mhs17_img_7862.jpg"
                                class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Rodamientos</h5>
                                <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                    additional content. This card has even longer content than the first to show that equal
                                    height action.</p>
                            </div>
                            <div class="card-footer">
                                <small class="text-muted">Last updated 3 mins ago</small>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row row-cols-1 row-cols-md-3 g-4 mt-1">
                    <div class="col">
                        <div class="card h-100">
                            <img src="https://marketplacer.imgix.net/M4/ogsbP1UpHomKzEkpR5qqYzFYE.jpg?auto=format&fm=pjpg&fit=max&w=1000&h=1000&s=18400be577047cb6aeef9fa7b2bb4562"
                                class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Cambio de llantas</h5>
                                <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                    additional content. This content is a little bit longer.</p>
                            </div>
                            <div class="card-footer">
                                <small class="text-muted">Last updated 3 mins ago</small>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card h-100">
                            <img src="https://http2.mlstatic.com/D_NQ_NP_709592-MCO31134745229_062019-O.jpg"
                                class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Cambio de guayas</h5>
                                <p class="card-text">This card has supporting text below as a natural lead-in to additional
                                    content.</p>
                            </div>
                            <div class="card-footer">
                                <small class="text-muted">Last updated 3 mins ago</small>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card h-100">
                            <img src="https://www.zapatillasmtb.com/blog/wp-content/uploads/2015/06/C%C3%B3mo-ajustar-el-cambio-de-marchas-en-una-bicicleta.jpg"
                                class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Ajuste de cambios</h5>
                                <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                    additional content. This card has even longer content than the first to show that equal
                                    height action.</p>
                            </div>
                            <div class="card-footer">
                                <small class="text-muted">Last updated 3 mins ago</small>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <footer class="mt-3" style="border-top: 1px solid #e0e0ef;">
                <h6 style="padding: 30px;  font-size: calc(0.8125rem - 0.05rem); color: #6c757d;">Copyrigth &#9400 2021. Todos los derechos reservados</h6>
            </footer>
        </main>
    </div>
  </div>
</template>

<script>
export default{
    data(){
        return{
            user: {
                nombre: 'Miguel',
                apellido: 'Mendez'
            },
            marca: 'BikeLatamShop',
            menu: [
                {title: 'Inicio'+'<h1>hola</h1>'},
                {title: 'Inicio1'+'<h1>hola</h1>'},
                {title: 'Inicio2'+'<h1>hola</h1>'},
                {title: 'Inicio3'+'<h1>hola</h1>'}
            ]
        }        
    }
}

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

li a{
    color: #686868;
    padding-left: 3rem;
}

a:hover{
    color: #3a3f51;
}

aside li{
    padding-top: 1rem;
    text-align: left;
}

ul{
    padding-left: 0;
}

img{
    height: 181px;
}

span{
    margin-left: .5rem;
}
</style>