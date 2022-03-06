<template>
  <div>
    <!-- Navigation bar -->
    <!--    <nav class="navbar is-warning is-fixed-top">-->
    <!--      <div class="navbar-brand">-->
    <!--        <div-->
    <!--          class="navbar-burger burger"-->
    <!--          data-target="navbarExampleTransparentExample"-->
    <!--        >-->
    <!--          <span></span>-->
    <!--          <span></span>-->
    <!--          <span></span>-->
    <!--        </div>-->
    <!--      </div>-->

    <!--      <div id="navbarExampleTransparentExample" class="navbar-menu">-->
    <!--        <div class="navbar-end">-->
    <!--          <a class="navbar-item" href="#about">-->
    <!--            <span class="icon">-->
    <!--              <i class="fas fa-info"></i>-->
    <!--            </span>-->
    <!--            <span>About</span>-->
    <!--          </a>-->
    <!--          <a class="navbar-item" href="#services">-->
    <!--            <span class="icon">-->
    <!--              <i class="fas fa-bars"></i>-->
    <!--            </span>-->
    <!--            <span>Services</span>-->
    <!--          </a>-->
    <!--          <a class="navbar-item" href="#resume">-->
    <!--            <span class="icon">-->
    <!--              <i class="fas fa-file-alt"></i>-->
    <!--            </span>-->
    <!--            <span>Resume</span>-->
    <!--          </a>-->
    <!--          <a class="navbar-item" href="#portfolio">-->
    <!--            <span class="icon">-->
    <!--              <i class="fas fa-th-list"></i>-->
    <!--            </span>-->
    <!--            <span>Portfolio</span>-->
    <!--          </a>-->
    <!--          <a class="navbar-item" href="#contact">-->
    <!--            <span class="icon">-->
    <!--              <i class="fas fa-envelope"></i>-->
    <!--            </span>-->
    <!--            <span>Contact</span>-->
    <!--          </a>-->
    <!--        </div>-->
    <!--      </div>-->
    <!--    </nav>-->

    <!-- Header -->
    <section class="hero is-warning is-fullheight is-fullheight-with-navbar">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column is-one-fifth-tablet">
              <figure class="image is-128x128" style="margin: auto">
                <img src="./assets/icon_from_natio.png" class="is-rounded" />
              </figure>
            </div>

            <div class="column is-four-fifths-tablet has-text-centered-mobile">
              Hello! I am
              <h1 class="title is-1">Lisach0w0</h1>
              <h2 class="subtitle is-3">Twitch Virtual Streamer</h2>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- About -->
    <section class="section" id="about">
      <!-- Title -->
      <div class="section-heading">
        <h3 class="title is-2">About Me</h3>
        <h4 class="subtitle is-5">Jack of all trades, master of "some"</h4>
        <div class="container">
          <p>
            りさちです、うるさめな揺れるVstreamerです！よろしくお願いします🥰
            i'm Lisa. Japanese Vtuber, Virtual Streamer. please call me Lisach！
            mainly Playing Fortnite and Apex！I will play a competitive game, so
            I will deliver it to win happily 💪🏻 I'm studying English because I
            want to make it a global channel.
          </p>
        </div>
      </div>

      <div class="columns has-same-height is-gapless">
        <div class="column">
          <!-- Profile -->
          <div class="card">
            <div class="card-content">
              <h3 class="title is-4">Profile</h3>

              <div class="content">
                <table class="table-profile">
                  <tr>
                    <th colspan="1"></th>
                    <th colspan="2"></th>
                  </tr>
                  <tr>
                    <td>Age:</td>
                    <td>20</td>
                  </tr>
                  <tr>
                    <td>height:</td>
                    <td>167cm</td>
                  </tr>
                  <tr>
                    <td>weight:</td>
                    <td>3 apples</td>
                  </tr>
                  <tr>
                    <td>melon:</td>
                    <td>2 melons</td>
                  </tr>
                  <tr>
                    <td>icon:</td>
                    <td>⚡🍈</td>
                  </tr>
                  <tr>
                    <td>tag:</td>
                    <td>#りさちClips, #りさ絵っち</td>
                  </tr>
                </table>
              </div>
              <br />
              <div class="buttons has-addons is-centered">
                <a href="https://www.twitch.tv/lisach0w0" class="button is-link"
                  >Twitch</a
                >
                <a href="https://twitter.com/Lisach0w0" class="button is-link"
                  >Twitter</a
                >
                <a
                  href="https://www.youtube.com/channel/UC6w_BzjW0IqDb7KYENCyP2g"
                  class="button is-link"
                  >Youtube</a
                >
                <a href="https://github.com/lisach0w0" class="button is-link"
                  >Github</a
                >
                <a href="https://wlo.link/@lisach0w0" class="button is-link"
                  >Another Links</a
                >
              </div>
            </div>
          </div>
        </div>
        <!--        <div class="column">-->
        <!--          &lt;!&ndash; Profile picture &ndash;&gt;-->
        <!--          <div class="card">-->
        <!--            <div class="card-image">-->
        <!--              <figure class="image is-4by3">-->
        <!--                <img-->
        <!--                  src="https://source.unsplash.com/random/1280x960"-->
        <!--                  alt="Placeholder image"-->
        <!--                />-->
        <!--              </figure>-->
        <!--            </div>-->
        <!--          </div>-->
        <!--        </div>-->
        <div class="column">
          <!-- Skills -->
          <div class="card">
            <div class="card-content skills-content">
              <h3 class="title is-4">Skills</h3>
              <div class="content">
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>Fortnite:</strong>
                        <br />
                        <progress
                          class="progress is-primary"
                          value="70"
                          max="100"
                        ></progress>
                      </p>
                    </div>
                  </div>
                </article>

                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>Apex:</strong>
                        <br />
                        <progress
                          class="progress is-primary"
                          value="25"
                          max="100"
                        ></progress>
                      </p>
                    </div>
                  </div>
                </article>
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>Varolant:</strong>
                        <br />
                        <progress
                          class="progress is-primary"
                          value="75"
                          max="100"
                        ></progress>
                      </p>
                    </div>
                  </div>
                </article>
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>HTML5/CSS3</strong>
                        <br />
                        <progress
                          class="progress is-primary"
                          value="95"
                          max="100"
                        ></progress>
                      </p>
                    </div>
                  </div>
                </article>
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>Databases</strong>
                        <br />
                        <progress
                          class="progress is-primary"
                          value="66"
                          max="100"
                        ></progress>
                      </p>
                    </div>
                  </div>
                </article>
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>Databases</strong>
                        <br />
                        <progress
                          class="progress is-primary"
                          value="66"
                          max="100"
                        ></progress>
                      </p>
                    </div>
                  </div>
                </article>
                <article class="media">
                  <div class="media-content">
                    <div class="content">
                      <p>
                        <strong>Databases</strong>
                        <br />
                        <progress
                          class="progress is-primary"
                          value="66"
                          max="100"
                        ></progress>
                      </p>
                    </div>
                  </div>
                </article>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Skills tags -->
    <!-- <br>
          <div class="tags custom-tags">
            <span class="tag is-light">Node.js</span><span class="tag is-light">Express.js</span><span class="tag is-light">VueJS</span><span
              class="tag is-light">JavaScript</span><span class="tag is-light">HTML5</span><span class="tag is-light">Canvas</span><span
              class="tag is-light">CSS3</span><span class="tag is-light">Bulma</span><span class="tag is-light">Bootstrap</span><span
              class="tag is-light">jQuery</span><span class="tag is-light">Pug</span><span class="tag is-light">Stylus</span><span
              class="tag is-light">SASS/SCSS</span><span class="tag is-light">Webpack</span><span class="tag is-light">Git</span><span
              class="tag is-light">ASP.NET Web Forms</span><span class="tag is-light">MSSQL</span><span class="tag is-light">MongoDB</span><span
              class="tag is-light">Apache Cordova</span><span class="tag is-light">Chrome Extensions</span>
          </div> -->
    <!-- Services -->
    <section class="section" id="services">
      <div class="section-heading">
        <h3 class="title is-2">Services</h3>
        <h4 class="subtitle is-5">What can I do for you?</h4>
      </div>
      <div class="container">
        <div class="columns">
          <div class="column">
            <div class="box">
              <div class="content">
                <h4 class="title is-5">Front End Web Development</h4>
                Develop Front End using latest standards with HTML5/CSS3 with
                added funtionality using JavaScript and Vue.js.
              </div>
            </div>
          </div>
          <div class="column">
            <div class="box">
              <div class="content">
                <h4 class="title is-5">Back End Web Development</h4>
                Develop Back End application/service using Node.js or ASP .NET
                and SQL server or Mongo DB databases.
              </div>
            </div>
          </div>
        </div>
        <div class="columns">
          <div class="column">
            <div class="box">
              <div class="content">
                <h4 class="title is-5">Front End Web Development</h4>
                Develop Front End using latest standards with HTML5/CSS3 with
                added funtionality using JavaScript and Vue.js.
              </div>
            </div>
          </div>
          <div class="column">
            <div class="box">
              <div class="content">
                <h4 class="title is-5">Back End Web Development</h4>
                Develop Back End application/service using Node.js or ASP .NET
                and SQL server or Mongo DB databases.
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Resume -->
    <section class="section" id="resume">
      <div class="section-heading">
        <h3 class="title is-2">Resume</h3>
        <h4 class="subtitle is-5">More about my past</h4>
        <a href="#" class="button is-link is-medium">
          <span class="icon">
            <i class="fas fa-file-alt"></i>
          </span>
          <span>Download My Resume</span>
        </a>
      </div>
    </section>
    <!-- Portfolio -->
    <section class="section" id="portfolio">
      <div class="container">
        <div class="section-heading">
          <h3 class="title is-2">Portfolio</h3>
          <h4 class="subtitle is-5">My latest works</h4>
        </div>
        <br />

        <div class="container portfolio-container">
          <div class="columns">
            <div class="column is-4">
              <!-- admin -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Admin <small>(Light)</small></span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-danger">WIP</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Admin template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/admin.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/admin.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!-- cards -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Cards</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">?</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Cards template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/cards.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/cards.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!-- forum -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Forum</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">Mobile</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Hero template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/forum.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/forum.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!-- insta album -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>InstaAlbum</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">Mobile</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Landing template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/instaAlbum.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/instaAlbum.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!-- landing -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Landing</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">Mobile</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Landing template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/landing.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/landing.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
            </div>
            <div class="column is-4">
              <!-- band -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Band</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">?</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Band template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/band.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/band.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!-- cheatsheet -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Cheatsheet</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">?</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Cheatsheet template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/cheatsheet.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/cheatsheet.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!-- hero -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Hero</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">?</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Hero template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/hero.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/hero.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!--kanban -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Kanban</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">?</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Kanban template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/kanban.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/kanban.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!-- login -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Login</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">Mobile</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Login template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/login.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/login.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
            </div>
            <div class="column is-4">
              <!-- blog -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Blog</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-danger">WIP</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Blog template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/blog.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/blog.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!-- cover -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Cover</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">Mobile</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Cover template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/cover.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/cover.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!--inbox -->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Inbox</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">Mobile</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Inbox template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/inbox.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/inbox.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!--kanban with functional search-->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Kanban with Search box</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">?</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="Kanban template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a
                    href="templates/kanban[search].html"
                    class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/kanban[search].html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
              <!--tabs-->
              <div class="card">
                <header class="card-header">
                  <p class="card-header-title">
                    <span>Modal Cards</span>
                    <span class="is-pulled-right">
                      <a
                        href="https://github.com/jgthms/bulma/releases/tag/0.7.2"
                      >
                        <span class="tag is-default">v0.7.2</span>
                      </a>
                      <span class="tag is-default">Desktop</span>
                      <span class="tag is-default">?</span>
                    </span>
                  </p>
                </header>
                <div class="card-content">
                  <figure class="image">
                    <img
                      src="https://dummyimage.com/555x255/000/fff"
                      alt="modal-cards template screenshot"
                    />
                  </figure>
                </div>
                <footer class="card-footer">
                  <a href="templates/modal-cards.html" class="card-footer-item"
                    >Preview</a
                  >
                  <a
                    href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/modal-cards.html"
                    class="card-footer-item"
                    >Source Code</a
                  >
                </footer>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Achievement Level -->
    <!-- <section class="section">
      <nav class="level">
        <div class="level-item has-text-centered">
          <div>
            <p class="heading">Tweets</p>
            <p class="title">3,456</p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <p class="heading">Following</p>
            <p class="title">123</p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <p class="heading">Followers</p>
            <p class="title">456K</p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <p class="heading">Likes</p>
            <p class="title">789</p>
          </div>
        </div>
      </nav>
    </section> -->
    <!-- Contact -->
    <section class="section" id="contact">
      <div class="container">
        <div class="section-heading">
          <h3 class="title is-2">Contact</h3>
          <h4 class="subtitle is-5">Get in touch</h4>
        </div>
        <br />
        <div class="columns">
          <div class="column is-6 is-offset-3">
            <div class="box">
              <div class="field">
                <label class="label">Name</label>
                <div class="control">
                  <input class="input" type="text" placeholder="Text input" />
                </div>
              </div>
              <div class="field">
                <label class="label">Email</label>
                <div class="control has-icons-left">
                  <input
                    class="input"
                    type="email"
                    placeholder="Email input"
                    value=""
                  />
                  <span class="icon is-small is-left">
                    <i class="fas fa-envelope"></i>
                  </span>
                </div>
              </div>
              <div class="field">
                <label class="label">Message</label>
                <div class="control">
                  <textarea class="textarea" placeholder="Textarea"></textarea>
                </div>
              </div>
              <div class="field is-grouped has-text-centered">
                <div class="control">
                  <button class="button is-link is-large">
                    <span class="icon">
                      <i class="fas fa-envelope"></i>
                    </span>
                    <span>Submit</span>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="section-heading">
        <p>
          <strong>Bulma Personal Template</strong> by
          <a href="https://mubaidr.js.org">Muhammad Ubaid Raza</a>. The source
          code is licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>.
        </p>
      </div>
    </footer>
  </div>
  <!--  <nav>-->
  <!--    <router-link to="/">Home</router-link> |-->
  <!--    <router-link to="/about">About</router-link>-->
  <!--  </nav>-->
  <!--  <router-view />-->
</template>

<style lang="scss">
@import "bulma/bulma.sass";
nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.has-same-height .card {
  height: 500px;
  overflow: hidden;
}

.card-content h3 {
  text-align: center;
}

.table-profile td,
th {
  border: none !important;
}

.table-profile td:first-of-type {
  font-weight: bold;
}

.skills-content .media {
  margin: 0 !important;
  padding: 4px !important;
  border: 0 !important;
}

.skills-content .progress {
  height: 4px !important;
}

.custom-tags {
  text-align: center !important;
  display: block;
}

.portfolio-container .card {
  margin-bottom: 2em;
}

.section-heading {
  text-align: center;
  margin-top: 1em;
  margin-bottom: 6em;
}
</style>
