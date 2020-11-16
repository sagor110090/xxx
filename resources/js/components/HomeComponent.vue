<template>
  <div>
    <nav class="navbar navbar-dark sticky-top flex-md-nowrap p-0 shadow sticky">
      <a class="navbar-brand col-md-3 col-lg-2 mr-0 px-3" href="#"
        ><img src="/image/logo.png" alt="" />
      </a>
      <!-- <button class="navbar-toggler position-absolute d-md-none collapsed" type="button" data-toggle="collapse"
        data-target="#sidebarMenu" aria-controls="sidebarMenu" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button> -->
      <!-- <input class="form-control form-control-dark w-100" type="text" placeholder="Search" aria-label="Search">
    <ul class="navbar-nav px-3">
        <li class="nav-item text-nowrap">
            <a class="nav-link" href="#">Sign out</a>
        </li>
    </ul> -->
      <div class="col-md-12">
        <div class="row">
          <div class="col-md-5">
            <div class="row">
              <div class="col-md-4">
                <img src="/image/ledy.png" alt="" />
              </div>
              <div class="col-md-6">
                <div class="input-group mt-4">
                  <div class="input-group-prepend bg-dark">
                    <span class="input-group-text" id="basic-addon1"
                      ><i class="fa fa-search" aria-hidden="true"></i
                    ></span>
                  </div>
                  <input
                    type="text"
                    class="form-control textInput"
                    placeholder="Search"
                    aria-label="Username"
                    aria-describedby="basic-addon1"
                  />
                </div>
              </div>
              <div class="col-md-2">
                <img src="/image/icon.png" alt="" />
              </div>
            </div>
          </div>
          <div class="col-md-1"></div>
          <div class="col-md-5">
            <div class="col-md-12">
              <div class="row">
                <div class="col-md-2 mt-2">
                  <li class="dropdown language-selector">
                    <a
                      href="#"
                      class="dropdown-toggle"
                      data-toggle="dropdown"
                      data-close-others="true"
                    >
                      <img src="/image/dtogwucagda11.PNG" class="ln-image" />
                    </a>
                    <ul class="dropdown-menu pull-right">
                      <li>
                        <a href="#">
                          <img
                            src="assets/images/flag-de.png"
                            class="ln-image"
                          />
                          <span>Deutsch</span>
                        </a>
                      </li>
                    </ul>
                  </li>
                </div>
                <div class="col-md-2 mt-4">
                  <img src="/image/login.png" alt="" />
                </div>
                <div class="col-md-2">
                  <img src="/image/sinup.png" alt="" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <div class="container-fluid">
      <div class="row">
        <nav
          id="sidebarMenu"
          class="col-md-3 col-lg-2 d-md-block bg-light sidebar collapse l-top"
        >
          <div class="sidebar-sticky pt-3">
            <ul class="nav flex-column ml-4 s-lv">
                <p>Larem Ipsum</p>
              <li class="nav-item">
                <a class="nav-link btn s-red-btn" href="#">
                  <i class="fa fa-address-card" style="font-size:24px;color:white"></i>
                   <span class="white-text">  SedCards  </span>
                </a>
              </li>
              <li class="nav-item mt-2">
                <a class="nav-link btn" href="#">
                  <i class="fa fa-map-marker" style="font-size:24px;color:white"></i>
                   <span class="white-text">  Location  </span>
                </a>
              </li>
              <li class="nav-item mt-2">
                <a class="nav-link btn" href="#">
                  <i class="fa fa-search" style="font-size:24px;color:white"></i>
                   <span class="white-text">  Search  </span>
                </a>
              </li>
              <!-- <li class="nav-item">
                <a class="nav-link" href="#">
                  <span data-feather="file"></span>
                  Orders
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <span data-feather="shopping-cart"></span>
                  Products
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <span data-feather="users"></span>
                  Customers
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <span data-feather="bar-chart-2"></span>
                  Reports
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <span data-feather="layers"></span>
                  Integrations
                </a>
              </li> -->
            </ul>
          </div>
        </nav>

        <main role="main" class="col-md-9 ml-sm-auto col-lg-10 px-md-4">
          <div class="container l-top">
            <div class="row">
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
              <div class="col-lg-3 col-md-4 col-sm-12 mt-3">
                <img src="/image/card.png" alt="image" class="img-responsive" />
              </div>
            </div>
          </div>
        </main>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    console.log("Component mounted.");
  },
};
</script>
<style  scoped>
.textInput {
  height: 40px;
  border: 1px solid #fefefe;
  border-radius: 6px;
  background: transparent;
  color: #fefefe;
  outline: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  box-shadow: 0 0 11px 1px #bf0345, inset 0 0 11px 1px #bf0345;
}
.ln-image {
  width: 51px;
  border-radius: 47px;
}
.img-responsive {
  display: block;
  max-width: 100%;
  height: auto;
}
.s-lv{
    color: #747474;
}
.s-red-btn{
    background: #bf0345;
    box-shadow: 0 0 11px 1px #bf0345, inset 0 0 11px 1px #bf0345;
}
.white-text{
    color: #fff;
}
</style>
