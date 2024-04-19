<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Jising social</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-primary">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">JISING SOCIAL FOUNDATION</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  service
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">education</a></li>
                  <li><a class="dropdown-item" href="#">Scholarship</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">camping</a></li>
                </ul>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="#">Mission</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Donate</a>
              </li>
              <li class="nav-item active">
                <a class="nav-link" href="contact">Team</a>
              </li>
              
            </ul>
            
            <div class="mx-1">
              <button type="button" class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#loginModal">Login</button>
              <button type="button" class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#signupModal">SingUp</button>

            </div>
            

            <!--login Modal -->
            <div class="modal fade" id="loginModal" tabindex="-1" aria-labelledby="loginModalLabel" aria-hidden="true">
              <div class="modal-dialog">
                <div class="modal-content">
                  <div class="modal-header">
                    <h1 class="modal-title fs-5" id="loginModalLabel">Login to Jising social</h1>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                  </div>
                  <div class="modal-body">
                    <div class="mb-3 row">
                      <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
                      <div class="col-sm-10">
                        <input type="email" class="form-control" id="inputemail">
                      </div>
                    </div>
                    <div class="mb-3 row">
                      <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                      <div class="col-sm-10">
                        <input type="password" class="form-control" id="inputPassword">
                      </div>
                    </div>
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-success" data-bs-dismiss="modal">submit</button>
                    
                  </div>
                </div>
              </div>
            </div>

            <!-- signup Modal -->
            <div class="modal fade" id="signupModal" tabindex="-1" aria-labelledby="signupModalLabel" aria-hidden="true">
              <div class="modal-dialog">
                <div class="modal-content">
                  <div class="modal-header">
                    <h1 class="modal-title fs-5" id="signupModalLabel">Get an Jising social</h1>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                  </div>
                  <div class="modal-body">
                    <div class="mb-3 row">
                      <label for="staticEmail" class="col-sm-2 col-form-label">Full Name</label>
                      <div class="col-sm-10">
                        <input type="email" class="form-control" id="inputemail">
                      </div>
                    </div>
                    <div class="mb-3 row">
                      <label for="staticEmail" class="col-sm-2 col-form-label">Email address</label>
                      <div class="col-sm-10">
                        <input type="email" class="form-control" id="inputemail">
                      </div>
                    </div>
                    <div class="mb-3 row">
                      <label for="inputPassword" class="col-sm-2 col-form-label">create Password</label>
                      <div class="col-sm-10">
                        <input type="password" class="form-control" id="inputPassword">
                      </div>
                    </div>
                    <div class="mb-3 row">
                      <label for="inputPassword" class="col-sm-2 col-form-label">comfirm Password</label>
                      <div class="col-sm-10">
                        <input type="password" class="form-control" id="inputPassword">
                      </div>
                    </div>
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-success" data-bs-dismiss="modal">submit</button>
                    <button type="button" class="btn btn-primary">Creat Account</button>
                    
                  </div>
                  </div>
                  
                </div>
              </div>
            </div>             
      </nav>

      <div class="team">
        <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active" data-bs-interval="10000">
              <img src="image/pic (1).jpeg" height="680" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h5>Jising Social Foundation</h5>
                <p>Building a bether tomorrow,Together.</p>
                
              </div>
            </div>
            <div class="carousel-item" data-bs-interval="2000">
              <img src="image/pic (4).jpeg" height="680" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h5>Breakin Barriers</h5>
                <p>Some representative placeholder content for the second slide.</p>            
              </div>
            </div>
            <div class="carousel-item">
              <img src="image/pic (5).jpeg" height="680" class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h5>Revolutionizing Learning for All</h5>
                <p>Some representative placeholder content for the third slide.</p>      
              </div>
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>

      </div> 

      <div class="container my-5">
        <div class="row mb-2">
            <div class="col-md-6">
              <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col p-4 d-flex flex-column position-static">
                  <strong class="d-inline-block mb-2 text-primary">Meet Us</strong>
                  <h3 class="mb-0">Ishak Leemuk</h3>                  
                  <p class="card-text mb-auto">Fonder & Director</p>                 
                </div>
                <img lass="bd-placeholder-img" width="200" height="350" src="image/pit (1).jpg" alt="">
              </div>
            </div>
            <div class="col-md-6">
              <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col p-4 d-flex flex-column position-static">
                  <strong class="d-inline-block mb-2 text-success">Meet Us</strong>
                  <h3 class="mb-0">Jirimay Rabha</h3>                
                  <p class="mb-auto">Executive manager</p>  
                </div>
               <img lass="bd-placeholder-img" width="200" height="350" src="image/pit (2).jpg" alt="">
              </div>
            </div>
          </div>
      </div>
      <h3>Contact Us</h3>
      
      
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
  </body>
</html>
