# html-css-exercises

HTML/CSS practice exercises

## Exercises for lecture-7 # Модель CSS box.

- Підключити до css Normalize.css (https://necolas.github.io/normalize.css/)


- В секції Hero розташуйте блок col зліва, так що цей блок не перекривав фонову картинку. Фонова картинка bg-banner.jpg знаходяться в директорії [images](https://github.com/nikejanus/nikejanus.github.io/tree/main/images)

```html
<!-- Hero -->

      <div class="container" id="hero">
          <div class="hero" style="background: url(images/bg-banner.jpg)">
            <div class="container">
              <div class="row text-center">
                
                <div class="col">
                  <p class="h6 text-uppercase text-muted">Summer 2024</p>
                  <h2 class="hero-heading title">Fashion Collections</h2>
                  <div class="row">
                    <div class="col">
                      <p class="text-muted subtitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                  </div><a class="btn text" href="shop.html">Shop now</a>
                </div>
                
              </div>
            </div>
          </div>
      </div>

```
- В секції Divider розташуйте блок col справа, так що цей блок не перекривав фонову картинку. Фонова картинка divider-bg.jpg знаходяться в директорії [images](https://github.com/nikejanus/nikejanus.github.io/tree/main/images)

```html
<!-- Divider section-->
    <div class="bg-center bg-cover" style="background: url(images/divider-bg.jpg)">
      <div class="container">
        <div class="row">
          <div class="col">
            <h2 class="hero-heading">New watches collections</h2>
            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p><a class="btn btn-primary" href="#"> <i class="fas fa-dolly-flatbed"></i>Shop now</a>
          </div>
        </div>
      </div>
    </div>

```