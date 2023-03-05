# **Este trebajo** esta hecho para un **Fan de ferrari**

Aqui mi amigo **Angel** me pide que le haga una pagina web

## **Html**
```html
<div>
  <header>
    <img src="/" alt="">
    <h1></h1>
  </header>
  <main>
    <div>
      <article>
        <div>
          <img src="/" alt="">
          <h1></h1>
        </div>
      </article>
      <article>
        <div>
          <img src="/" alt="">
          <h1></h1>
        </div>
      </article>
      <article>
        <div>
          <img src="/" alt="">
          <h1></h1>
        </div>
      </article>
      <article>
        <div>
          <img src="/" alt="">
          <h1></h1>
        </div>
      </article>
      <article>
        <div>
          <img src="/" alt="">
          <h1></h1>
        </div>
      </article>
    </div>
  </main>
  <footer>
    <br>
    <a></a>
    <a></a>
  </footer>
</div>
```

## CSS
```css
:root{
  /* Fonts */
  --font-osw: 'Oswald', sans-serif;
  --font-ral: 'Raleway', sans-serif;
  /* Colors Primaria */
  --white: #d5d5d5;
  --amar: #d1e000;
  /* Colors Neutro */
  --azul-grisaceo: #1f2730;
  --azul-grisaceo-oscuro: #141a1f;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color: var(--azul-grisaceo-oscuro);
  font-family: var(--font-ral);
  font-size: 18px;
}

.encb {
  width: 100%;
  height: 50px;
  margin-bottom: 15px;
  background-color: var(--azul-grisaceo);
  color: var(--white);
  display: flex;
  padding: 5px 10px;
  gap: 10px;
  align-items: center;
  justify-content: center;
}
.encb__logo {
  width: 40px;
  height: 40px;
}
.encb__logtitle {
  font-family: var(--font-ral);
  font-size: 1.25em;
  font-weight: 500;
  text-align: center;
  letter-spacing: 2.5px;
}
.content {
  margin: 20px 60px;
  width: 500px;
  height: 900px;
  background-color: var(--azul-grisaceo);
  border-radius: 12px;
}
.content__articles {
  padding: 15px 10px;
  width: 480px;
  height: 870px;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr;
  grid-template-areas: "art1" "art2" "art3" "art4" "art5";
  overflow: hidden;
  gap: 20px;
}
.article1 {
  grid-area: art1;
  border-radius: 12px;
}
.article2 {
  grid-area: art2;
  border-radius: 12px;
}
.article3 {
  grid-area: art3;
  border-radius: 12px;
}
.article4 {
  grid-area: art4;
  border-radius: 12px;
}
.article5 {
  grid-area: art5;
  border-radius: 12px;
}
.imgCar5 {
  width: 300px;
}
.content__articles__article {
  background-color: var(--azul-grisaceo-oscuro);
}
.content__articles__article__imgCar {
  width: 200px;
  height: 120px;
}
```