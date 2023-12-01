<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
      integrity="sha384-mQ93GR66B00ZXjt0YO5KlohRA5SY2XofNolja27iH5P1pzapak7dF5+2HI4P"
      crossorigin="anonymous"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
      integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <title>Funding Binary Brix</title>
    <style>
      .navbar-nav .nav-item.active .nav-link {
        text-decoration: underline;
        padding-bottom: 10px; /* Adjust the value as needed */
      }
      #search-icon-btn {
        margin-left: -15px;
      }
      .btn-round {
        border-radius: 25px;
      }
      a.line {
        text-decoration: none;
        position: relative;
      }

      a.line::before {
        content: "";
        position: absolute;
        bottom: -7px; /* Adjust this value to control the underline's position */
        left: 0;
        width: 100%;
        height: 5px; /* Adjust this value to control the underline's thickness */
        background-color: #0d6efd; /* Adjust the color as needed */
      }
      .accordion-button {
        padding: 0px;
        width: fit-content;
      }
  .accordion-flush .accordion-item {
    border-right: 0;
    border-left: 0;
    border-radius: 0;
    border-bottom: 0;
}
.accordion-button::after {
    flex-shrink: 0;
    width: 1.25rem;
    height: 1.25rem;
    margin-left: auto;
    content: url('data:image/svg+xml,%3csvg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="%230069d9"%3e%3cpath fill-rule="evenodd" d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z"/%3e%3c/svg%3e');
    background-repeat: no-repeat;
    background-size: 1.25rem;
    transition: transform .2s ease-in-out;
    background-image: none;
}

    </style>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light px-5">
      <a class="navbar-brand" href="#"><b>LOGO</b></a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item mx-lg-4">
            <a class="nav-link" href="Advantage.html">Home </a>
          </li>
          <li class="nav-item mx-lg-4">
            <a class="nav-link" href="funding.html">Funding </a>
          </li>
          <li class="nav-item mx-lg-4 active">
            <a class="nav-link" href="index.html">Third</a>
          </li>
          <li class="nav-item mx-lg-4">
            <a class="nav-link" href="shows1.html">Fourth</a>
          </li>
          <li class="nav-item mx-lg-4">
            <a class="nav-link" href="shows2.html">Fifth</a>
          </li>
        </ul>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">
              <i class="fas fa-search"></i>
            </a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="px-md-5">
      
      <div class="container-fluid mb-4">
        <div class="row mt-4">
          <div class="col-md-6">
            <h4>Funding Search</h4>
          </div>
          <div class="col-md-6 d-flex justify-content-md-end align-items-center">
            <p class="mt-0 mr-3 text-center">
              <i
                class="fas fa-user-circle"
                style="margin-right: 7px; color: #0069d9"
              ></i
              ><b>User Profile</b><br />Subtitle
            </p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-8 mx-auto">
            <div class="input-group my-3">
              <div class="input-group-prepend">
                <span class="input-group-text"
                  ><i class="fas fa-search"></i
                ></span>
              </div>
              <input
                type="text"
                class="form-control"
                placeholder="Quick Search..."
                aria-label="Search"
                aria-describedby="search-icon-btn"
                style="border: 1px solid #6b8dfb"
              />
              <div class="input-group-append">
                <button
                  class="btn btn-primary px-5 btn-round"
                  type="button"
                  id="search-icon-btn"
                >
                  Search
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <h5>Search by Sector or Geography</h5>
    </div>

    <div class="jumbotron my-5" style="background-color: #edf1fe">
      <div class="d-flex justify-content-center text-center">
        <div class="accordion accordion-flush" id="accordionFlushExample">
          <div class="accordion-item" style="background-color: transparent">
            <h2 class="accordion-header d-flex justify-content-center" id="flush-headingOne">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseOne"
                aria-expanded="false"
                aria-controls="flush-collapseOne"
                style="
                  border-bottom: 0px;
                  background-color: transparent;
                  box-shadow: none;
                "
              >
                <h5 class="display-5">
                  I'm looking for <a class="line" href="">Funding Type</a>
                </h5>
              </button>
            </h2>
            <div
              id="flush-collapseOne"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingOne"
              data-bs-parent="#accordionFlushExample"
            >
              <div class="accordion-body">
                Placeholder content for this accordion, which is intended to
                demonstrate the <code>.accordion-flush</code> class. This is the
                first item's accordion body.
              </div>
            </div>
          </div>
          <div class="accordion-item" style="background-color: transparent">
            <h2 class="accordion-header d-flex justify-content-center" id="flush-headingTwo">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseTwo"
                aria-expanded="false"
                aria-controls="flush-collapseTwo"
                style="
                  border: 0px;
                  background-color: transparent;
                  box-shadow: none;
                "
              >
                <h1 class="display-5">
                  active in <a class="line" href="">All Sectors</a>
                </h1>
              </button>
            </h2>
            <div
              id="flush-collapseTwo"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingTwo"
              data-bs-parent="#accordionFlushExample"
            >
              <div class="accordion-body">
                Placeholder content for this accordion, which is intended to
                demonstrate the <code>.accordion-flush</code> class. This is the
                second item's accordion body. Let's imagine this being filled
                with some actual content.
              </div>
            </div>
          </div>
          <div class="accordion-item" style="background-color: transparent">
            <h2 class="accordion-header d-flex justify-content-center" id="flush-headingThree">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#flush-collapseThree"
                aria-expanded="false"
                aria-controls="flush-collapseThree"
                style="
                  border: 0px;
                  background-color: transparent;
                  box-shadow: none;
                "
              >
                <h1 class="display-5">
                  in <a class="line" href="">All Geographies</a>
                </h1>
              </button>
            </h2>

            <div
              id="flush-collapseThree"
              class="accordion-collapse collapse"
              aria-labelledby="flush-headingThree"
              data-bs-parent="#accordionFlushExample"
            >
              <div class="accordion-body">
                Placeholder content for this accordion, which is intended to
                demonstrate the <code>.accordion-flush</code> class. This is the
                third item's accordion body. Nothing more exciting happening
                here in terms of content, but just filling up the space to make
                it look, at least at first glance, a bit more representative of
                how this would look in a real-world application.
              </div>
            </div>
          </div>
          <div class="d-flex justify-content-center mt-5">
            <button
              class="btn btn-primary px-5 btn-round"
              type="button"
              id="search-icon-btn"
            >
              Show Results
            </button>
          </div>
        </div>
      </div>
    </div>

    <!-- Your page content goes here -->

    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
  </body>
</html>
