- Create a layout according to the design shown below.

![Creating lists Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/lists/ex-1.png)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Work on typography in detail.
<!DOCTYPE html>
<html lang="end">
    <head> 
        <meta charset="UTF-8">
        <title> Hackant </title>
        <script src="https://kit.fontawesome.com/ef43d9bbc3.js" crossorigin="anonymous"></script>
        <link rel="stylesheet" href="assets/style.css">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;900&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <ul class=" header flex container">
                <a href="#"><li>Home</li></a>
                <a href="#"><li>About</li></a>
                <a href="#"><li>Faqs</li></a>
                <a href="#"><li>Program</li></a>
                <a href="#"><li>Contact</li></a>
            </ul>
        </header>
      <main class="bkg">
          <section class="list container flex">
              <div class="block">
                  <ol>
                      <li>Home</li>
                      <li>Page</li>
                      <li>Services</li>
                      <li>About Us</li>
                      <li>Portfolio</li>
                      <li value="20">Pricing</li>
                      <li>News</li>
                      <li>Testimonia</li>
                      <li>Contact Us</li>
                  </ol>

              </div>
              <div class="block block2">
                <ul>
                    <li>Home</li>
                    <li>Menu
                            <ol class="o1">
                            <li>Menu 1
                                <ul class="u1">
                                    <li>Sub Menu1</li>
                                    <li>Sub Menu2</li>
                                </ul>
                            </li>
                            <li>Menu 2</li>
                            <li>Menu 3</li>
                            <li>Menu 4</li>
                            <li>Menu 5</li>
                        </ol>
                    </li>
                    <li>How we work</li>
                    <li>About Us</li>
                    <li>Contact Us</li>
                </ul>

            </div>
            <div class="block block3">
                <ol>
                    <li>Home</li>
                    <li>Page</li>
                    <li>Services</li>
                    <li>About Us</li>
                    <li>Portfolio</li>
                    <li value="20">Pricing</li>
                    <li>News</li>
                    <li>Testimonia</li>
                    <li>Contact Us</li>
                </ol>
            </div>
            </section>
              <article class="article container">
                  <h2>What is lorem Ipsum</h2>
                  <p>Lorem ipsum dolor sit amet. Ex enim ratione ea omnis eligendi ut quibusdam exercitationem ea earum laudantium in omnis corporis et unde 
                      corrupti et nemo veritatis. Non molestias nesciunt quo quos culpa At doloremque consequatur rem sapiente dolores 
                      eum porro quas et quia praesentium in doloribus voluptatem.
                      orem ipsum dolor sit amet. Ex enim ratione ea omnis eligendi ut quibusdam exercitationem ea earum laudantium in omnis corporis et unde 
                      corrupti et nemo veritatis. Non molestias nesciunt quo quos culpa At doloremque consequatur rem sapiente dolores 
                      eum porro quas et quia praesentium in doloribus voluptatem.
                  </p>
                  <h2>What is lorem Ipsum</h2>
                  <p>Lorem ipsum dolor sit amet. Ex enim ratione ea omnis eligendi ut quibusdam exercitationem ea earum laudantium in omnis corporis et unde 
                      corrupti et nemo veritatis. Non molestias nesciunt quo quos culpa At doloremque consequatur rem sapiente dolores 
                      eum porro quas et quia praesentium in doloribus voluptatem.
                      orem ipsum dolor sit amet. Ex enim ratione ea omnis eligendi ut quibusdam exercitationem ea earum laudantium in omnis corporis et unde 
                      corrupti et nemo veritatis. Non molestias nesciunt quo quos culpa At doloremque consequatur rem sapiente dolores 
                      eum porro quas et quia praesentium in doloribus voluptatem.
                  </p>
                  <h2>lorem Ipsum</h2>
                  <h2>Dummy text</h2>
                  <p>Lorem ipsum dolor sit amet. Ex enim ratione ea omnis eligendi ut quibusdam exercitationem ea earum laudantium in omnis corporis et unde 
                      corrupti et nemo veritatis. Non molestias nesciunt quo quos culpa At doloremque consequatur rem sapiente dolores 
                      eum porro quas et quia praesentium in doloribus voluptatem.
                      orem ipsum dolor sit amet. Ex enim ratione ea omnis eligendi ut quibusdam exercitationem ea earum laudantium in omnis corporis et unde 
                      corrupti et nemo veritatis. Non molestias nesciunt quo quos culpa At doloremque consequatur rem sapiente dolores 
                      eum porro quas et quia praesentium in doloribus voluptatem.
                  </p>



              </article>

          </section>
      </main>
   </body>
   <footer>
    <ul class=" header flex container">
        <a href="#"><li>Home</li></a>
        <a href="#"><li>About</li></a>
        <a href="#"><li>Faqs</li></a>
        <a href="#"><li>Program</li></a>
        <a href="#"><li>Contact</li></a>
    </ul>
   </footer>
</html>
