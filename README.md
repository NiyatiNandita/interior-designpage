<!DOCTYPE html>
<html>
  <head>
    <title>interior page</title>
    <link rel="stylesheet" href="/newmy1.css" type="text/css" />
    <style>
    body {
  margin: 0;
  background-image: url(https://www.homestratosphere.com/wp-content/uploads/2019/08/Cool-black-living-room-design-aug16.jpg);
  background-size: cover;
}
header {
  height: 100px;
  background-color: black;
  opacity: 0.8;
  /* position: static; */
}
/* .hea {
  opacity: 0.6;
} */
.navbar {
  text-align: right;
}
#headerimg {
  width: 200px;
  height: 100px;
}
.nav-item {
  color: white;
  font-size: 20px;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  padding-right: 20px;
  text-decoration: none;
  position: relative;
  top: -75px;
}
.nav-item:hover {
  text-decoration: underline;
}
#header-btn {
  background-color: rgba(251, 251, 251, 0.899);
  font-size: 20px;
  color: black;
  padding: 10px 20px;
  border: 1px solid transparent;
  border-radius: 30px;
  position: relative;
  top: -75px;
  margin-right: 15px;
}
#header-btn:hover {
  background-color: rgb(130, 4, 4);
  color: white;
}
section {
  text-align: center;
  color: white;
  position: relative;
  bottom: -200px;
}

section > h1 {
  font-size: 85px;
  padding: 0;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}
section > p {
  font-size: 15px;
  padding: 0;
  /* margin: 0; */
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 0.5;
}
.custom-btn {
  font-size: 20px;
  background: none;
  padding: 10px 20px;
  border: 1px solid white;
  color: white;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.87);
  border-radius: 25px;
  margin-right: 20px;
  margin-top: 20px;
  font-style: italic;
}
.custom-btn:hover {
  background-color: white;
  color: black;
}
    </style>
  </head>
  <body>
    <header class="headerr">
      <img
        id="headerimg"
        src="https://www.shutterstock.com/image-vector/modern-interior-home-design-logo-600w-1728862156.jpg"
        alt=""
      />
      <nav class="navbar">
        <a class="nav-item" href="">Home</a>
        <a class="nav-item" href="">Kitchen</a>
        <a class="nav-item" href="">Dining</a>
        <a class="nav-item" href="">Bedroom</a>
        <a class="nav-item" href="">Backyard</a>
        <button id="header-btn">Log In</button>
      </nav>
    </header>
    <main>
      <section>
        <h1>DESIGN YOUR HOUSE</h1>
        <p>
          Get your house designed by one of the best interior designers in town.
          Give us a chance to make your dreams come true.
        </p>
        <div>
          <button class="custom-btn">Know More</button>
          <button class="custom-btn">Subscribe</button>
        </div>
      </section>
    </main>
  </body>
</html>
