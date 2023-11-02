# Project_ADS_DEVWEB2023
Atividade para a matéria de desenvolvimento web
<div class="page-wrap">
  <header class="site-header">
    <div class="global-announcement">
      <p>Confira nossas promoções <a href="#">clique aqui</a></p>
    </div>
    <nav class="site-nav">
      <ul>
        <li><a class="site-logo" href="#">Rei dos xiaomi</a></li>
        <li><a href="#">Redmi note 12</a></li>
        <li><a href="#">Redmi note 12 pro</a></li>
        <li><a href="#">Redmi note 13</a></li>
        <li><a href="#">Redmi note 13 pro</a></li>
        <li><a href="#">Outros modelos</a></li>
      </ul>
    </nav>
  </header>
  <main class="page-main">
    <h1>Promoções do momento</h1>
    <div class="product-filter">
      <fieldset>
        <legend>Ano de lançamento</legend>
        <ul>
          <li>
            <input id="wood" name="material" value="wood" type="radio">
            <label for="wood">2023</label>
          </li>
          <li>
            <input id="glass" name="material" value="glass" type="radio">
            <label for="glass">2022</label>
          </li>
          <li>
            <input id="metal" name="material" value="metal" type="radio">
            <label for="metal">Anteriores disponiveis</label>
          </li>
        </ul>
      </fieldset>
    </div>
    <ul class="products">
      <li class="card">
        <div class="card__text">
          <h2 class="card__title">
            <a class="card__link" href="#">Redmi note 12</a>
          </h2>
          <p class="product-price">$1.049,00</p>
          <div class="product-compare">
            <label for"compare-table1">Adicionar ao carrinho</label>
            <input id="compare-table1" name="compare" type="checkbox" value="compare">
          </div>
        </div>
        <div class="card__img">
          <img src="https://down-br.img.susercontent.com/file/br-11134207-23020-vkt3e84b6bnv5f" alt="minimal wooden desk with accompanying wood and metal chair." loading="lazy" width="750" height="750">
        </div>
      </li>
      <li class="card">
        <div class="card__text">
          <h2 class="card__title">
            <a class="card__link" href="#">Redmi note 12 pro</a>
          </h2>
          <p class="product-price">1.729,00</p>
          <div class="product-compare">
            <label for"compare-table2">Adicionar ao carrinho</label>
            <input id="compare-table2" name="compare" type="checkbox" value="compare">
          </div>
        </div>
        <div class="card__img">
          <img src="https://i.zst.com.br/thumbs/12/2e/2e/-977680868.jpg" alt="oak table with yellow legs" loading="lazy" width="750" height="750">
        </div>
      </li>
      <li class="card">
        <div class="card__text">
          <h2 class="card__title">
            <a class="card__link" href="#">Redmi note 13</a>
          </h2>
          <p class="product-price">$1.200,00</p>
          <div class="product-compare">
            <label for"compare-table3">Adicionar no carrinho</label>
            <input id="compare-table3" name="compare" type="checkbox" value="compare">
          </div>
        </div>
        <div class="card__img">
          <img src="https://t.ctcdn.com.br/SmmIDww3Ff0XDNANy9E08QfTS4I=/fit-in/400x400/filters:fill(transparent):watermark(wm/prd.png,-32p,center,1,none,15)/i802463.png" alt="a white table for two with matching chairs." loading="lazy" width="750" height="750">
        </div>
      </li>
      <li class="card">
        <div class="card__text">
          <h2 class="card__title">
            <a class="card__link" href="#">Redmi note 13 pro</a>
          </h2>
          <p class="product-price">1.900,00</p>
          <div class="product-compare">
            <label for"compare-table4">Adicionar ao carrinho</label>
            <input id="compare-table4" name="compare" type="checkbox" value="compare">
          </div>
        </div>
        <div class="card__img">
          <img src="https://www.hardware.com.br/wp-content/uploads/2023/09/Redmi-Note-13-Pro-Plus-.png" alt="white bedside table" loading="lazy" width="750" height="750">
        </div>
      </li>
    </ul>
  </main>
  </divdiv>
  <footer class="site-footer">
    <div class="footer-links">
      <h2>Modelos</h2>
      <ul>
        <li><a href="#">Redmi</a></li>
        <li><a href="#">Poco</a></li>
        <li><a href="#">Novos modelos</a></li>
        <li><a href="#">Promoção </a></li>
      </ul>
    </div>
    <div class="footer-links">
      <h2>Ajuda</h2>
      <ul>
        <li><a href="#">Perguntas frequentes</a></li>
        <li><a href="#">Entregas</a></li>
        <li><a href="#">Reembolsos</a></li>
        <li><a href="#">Garantia</a></li>
      </ul>
    </div>
    <div class="footer-links">
      <h2>Sobre a empresa</h2>
      <ul>
        <li><a href="#">Sobre nós</a></li>
        <li><a href="#">Contato</a></li>
        <li><a href="#">Carreiras</a></li>
        <li><a href="#">Lojas fíicas</a></li>
      </ul>                                                                                            
    </div>
    <div class="footer-legal">
      <p>Copyright &copy; 2023 Rei dos xiaomi, Inc.</p>
      <ul>
        <li><a href="#">Politica de privacidade</a></li>
        <li><a href="#">Termos de serviço</a></li>
        <li><a href="#">Politica de reembol
        <li><a href="#">Poco</a></li>
        <li><a href="#">Novos modelos</a></li>
        <li><a href="#">Promoção </a></li>
      </ul>
    </div>
    <div class="footer-links">

    //css

    @import url("https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Jost:wght@200;400;600&display=swap");

@mixin flex {
  display: flex;

  flex-direction: column;
}

@mixin flex-child {
  flex: 1 0 auto;
}

:root {
  --green: #166639;

  --interaction: #147373;
}

* {
  -webkit-box-sizing: border-box;

  -moz-box-sizing: border-box;

  box-sizing: border-box;

  margin: 0;

  padding: 0;
}

html {
  color: #333;

  font-family: "Jost", sans-serif;

  font-size: 100%;
}

img {
  max-width: 100%;

  width: auto;

  height: auto;
}

h1,
.h1 {
  font-size: 3rem;

  font-weight: 400;
}

h2,
.h2 {
  font-size: 2.25rem;
}

a:focus {
  outline: 1px solid;

  outline-offset: 1px;
}

.site-header {
  margin-bottom: 1.5rem;

  border-bottom: 8px solid var(--green);
}

.site-logo {
  color: var(--green);

  font-family: "Abril Fatface", cursive;

  font-size: 3rem;

  letter-spacing: 2px;

  text-decoration: none;

  &:hover,
  &:focus {
    background-color: var(--interaction);

    border-color: transparent;

    color: #fff !important;

    outline: none;
  }
}

.site-nav {
  display: flex;

  align-items: center;

  padding: 1rem;
}

.site-nav ul {
  display: flex;

  align-items: center;

  height: 100%;

  list-style: none;
}

.site-nav ul > li {
  margin-right: 8px;

  margin-top: 12px;

  &:first-child {
    margin-top: 0;
  }

  &:last-child {
    margin-right: 0;
  }
}

.site-nav ul > li > a {
  border: 2px solid transparent;

  color: var(--green);

  padding: 8px 16px;

  text-align: center;

  text-decoration: none;

  transition: all 0.2s ease-in-out;
}

.site-nav ul > li > a:hover,
.site-nav ul > li > a:focus {
  border-color: var(--interaction);

  color: var(--interaction);

  outline: none;
}

.global-announcement {
  background-color: var(--green);

  color: #fff;

  font-weight: 600;

  padding: 0.5rem;

  text-align: center;
}

.global-announcement a {
  color: #fff;
}

.site-footer {
  display: grid;

  grid-template-columns: repeat(3, minmax(10px, 1fr));

  justify-items: center;

  background-color: var(--green);

  color: #fff;

  padding: 2rem 5rem;
}

.footer-legal {
  text-align: center;

  grid-column: 1 / -1;

  justify-content: center;

  margin-top: 24px;
}

.footer-links {
  ul {
    list-style: none;
  }

  ul li {
    margin-bottom: 4px;

    &:last-child {
      margin-bottom: 0;
    }
  }

  a {
    color: #fff;

    text-decoration: none;

    &:hover {
      text-decoration: underline;
    }
  }
}

.footer-logo {
  align-items: center;

  color: #fff;

  display: inline-flex;

  text-decoration: none;

  margin-bottom: 8px;
}

.footer-logo > svg {
  margin-right: 8px;

  max-width: 75px;
}

.footer-logo span {
  font-family: "Tangerine", cursive;

  font-size: 4rem;
}

.footer-legal ul {
  list-style: none;

  margin-left: 0;

  margin-bottom: 0;
}

.footer-legal ul li {
  display: inline-block;
}

.footer-legal ul li a {
  color: #fff;

  display: inline-block;

  font-size: 0.88rem;

  font-weight: 600;

  padding: 4px;

  text-decoration: none;
}

.footer-legal ul li a:hover,
.breadcrumbs ul li a:focus {
  text-decoration: underline;
}

.footer-legal ul li ~ li::before {
  content: "|";
}

.page-main {
  display: grid;

  grid-template-columns: minmax(10px, 0.5fr) minmax(10px, 2.5fr);

  margin-bottom: 3rem;

  padding: 0 4rem;
}

.page-main h1 {
  grid-column: 1/-1;

  color: var(--green);

  margin-bottom: 1.5rem;
}

.products {
  display: grid;

  grid-template-columns: repeat(auto-fit, minmax(300px, 4fr));

  grid-gap: 2rem;

  row-gap: 1.5rem;

  list-style: none;
}

.product-filter fieldset {
  border: none;

  margin-bottom: 1rem;

  legend {
    font-size: 1.25rem;

    font-weight: 600;

    margin-bottom: 0.25rem;
  }

  > ul {
    list-style: none;
  }

  input {
    margin-right: 8px;
  }
}

.card {
  @include flex;

  border: 1px solid #000;

  border-radius: 4px;

  position: relative;

  &:hover {
    box-shadow: 0px 0px 4px 1px var(--interaction);
  }

  a:focus {
    text-decoration: underline;
  }

  &:focus-within {
    box-shadow: 0px 0px 4px 1px var(--interaction);

    a {
      text-deocration: none;

      &:focus {
        outline: none;
      }
    }
  }
}

.card__text {
  @include flex;

  @include flex-child;

  padding: 0.5rem 1rem;

  order: 1;

  * {
    margin-bottom: 0;
  }

  :last-child {
    margin-top: auto;
  }

  .card__title a {
    color: #333;

    font-weight: 200;

    text-decoration: none;
  }

  > * + * {
    margin-top: 0.5rem;
  }
}

.product-price {
  font-size: 0.9rem;

  font-weight: 600;
}

.product-compare {
  position: absolute;

  top: 0.5rem;

  right: 0.5rem;

  display: flex;

  align-items: center;

  background-color: #fff;

  border-radius: 4px;

  padding: 8px;

  border: 1px solid #333;

  transition: opacity 0.2s ease-in-out;

  opacity: 0;
}

.card:hover .product-compare {
  opacity: 1;
}

.product-compare:focus-within {
  opacity: 1;
}

.product-compare label {
  font-size: 0.9rem;

  margin-right: 8px;
}

.product-compare input {
  margin: 0 !important;
}
@import url("https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Jost:wght@200;400;600&display=swap");

@mixin flex {
  display: flex;

  flex-direction: column;
}

@mixin flex-child {
  flex: 1 0 auto;
}

:root {
  --green: #166639;

  --interaction: #147373;
}

* {
  -webkit-box-sizing: border-box;

  -moz-box-sizing: border-box;

  box-sizing: border-box;

  margin: 0;

  padding: 0;
}

html {
  color: #333;

  font-family: "Jost", sans-serif;

  font-size: 100%;
}

img {
  max-width: 100%;

  width: auto;

  height: auto;
}

h1,
.h1 {
  font-size: 3rem;

  font-weight: 400;
}

h2,
.h2 {
  font-size: 2.25rem;
}

a:focus {
  outline: 1px solid;

  outline-offset: 1px;
}

.site-header {
  margin-bottom: 1.5rem;

  border-bottom: 8px solid var(--green);
}

.site-logo {
  color: var(--green);

  font-family: "Abril Fatface", cursive;

  font-size: 3rem;

  letter-spacing: 2px;

  text-decoration: none;

  &:hover,
  &:focus {
    background-color: var(--interaction);

    border-color: transparent;

    color: #fff !important;

    outline: none;
  }
}

.site-nav {
  display: flex;

  align-items: center;

  padding: 1rem;
}

.site-nav ul {
  display: flex;

  align-items: center;

  height: 100%;

  list-style: none;
}

.site-nav ul > li {
  margin-right: 8px;

  margin-top: 12px;

  &:first-child {
    margin-top: 0;
  }

  &:last-child {
    margin-right: 0;
  }
}

.site-nav ul > li > a {
  border: 2px solid transparent;

  color: var(--green);

  padding: 8px 16px;

  text-align: center;

  text-decoration: none;

  transition: all 0.2s ease-in-out;
}

.site-nav ul > li > a:hover,
.site-nav ul > li > a:focus {
  border-color: var(--interaction);

  color: var(--interaction);

  outline: none;
}

.global-announcement {
  background-color: var(--green);

  color: #fff;

  font-weight: 600;

  padding: 0.5rem;

  text-align: center;
}

.global-announcement a {
  color: #fff;
}

.site-footer {
  display: grid;

  grid-template-columns: repeat(3, minmax(10px, 1fr));

  justify-items: center;

  background-color: var(--green);

  color: #fff;

  padding: 2rem 5rem;
}

.footer-legal {
  text-align: center;

  grid-column: 1 / -1;

  justify-content: center;

  margin-top: 24px;
}

.footer-links {
  ul {
    list-style: none;
  }

  ul li {
    margin-bottom: 4px;

    &:last-child {
      margin-bottom: 0;
    }
  }

  a {
    color: #fff;

    text-decoration: none;

    &:hover {
      text-decoration: underline;
    }
  }
}

.footer-logo {
  align-items: center;

  color: #fff;

  display: inline-flex;

  text-decoration: none;

  margin-bottom: 8px;
}

.footer-logo > svg {
  margin-right: 8px;

  max-width: 75px;
}

.footer-logo span {
  font-family: "Tangerine", cursive;

  font-size: 4rem;
}

.footer-legal ul {
  list-style: none;

  margin-left: 0;

  margin-bottom: 0;
}

.footer-legal ul li {
  display: inline-block;
}

.footer-legal ul li a {
  color: #fff;

  display: inline-block;

  font-size: 0.88rem;

  font-weight: 600;

  padding: 4px;

  text-decoration: none;
}

.footer-legal ul li a:hover,
.breadcrumbs ul li a:focus {
  text-decoration: underline;
}

.footer-legal ul li ~ li::before {
  content: "|";
}

.page-main {
  display: grid;

  grid-template-columns: minmax(10px, 0.5fr) minmax(10px, 2.5fr);

  margin-bottom: 3rem;

  padding: 0 4rem;
}

.page-main h1 {
  grid-column: 1/-1;

  color: var(--green);

  margin-bottom: 1.5rem;
}

.products {
  display: grid;

  grid-template-columns: repeat(auto-fit, minmax(300px, 4fr));

  grid-gap: 2rem;

  row-gap: 1.5rem;

  list-style: none;
}

.product-filter fieldset {
  border: none;

  margin-bottom: 1rem;

  legend {
    font-size: 1.25rem;

    font-weight: 600;

    margin-bottom: 0.25rem;
  }

  > ul {
    list-style: none;
  }

  input {
    margin-right: 8px;
  }
}

.card {
  @include flex;

  border: 1px solid #000;

  border-radius: 4px;

  position: relative;

  &:hover {
    box-shadow: 0px 0px 4px 1px var(--interaction);
  }

  a:focus {
    text-decoration: underline;
  }

  &:focus-within {
    box-shadow: 0px 0px 4px 1px var(--interaction);

    a {
      text-deocration: none;

      &:focus {
        outline: none;
      }
    }
  }
}

.card__text {
  @include flex;

  @include flex-child;

  padding: 0.5rem 1rem;

  order: 1;

  * {
    margin-bottom: 0;
  }

  :last-child {
    margin-top: auto;
  }

  .card__title a {
    color: #333;

    font-weight: 200;

    text-decoration: none;
  }

  > * + * {
    margin-top: 0.5rem;
  }
}

.product-price {
  font-size: 0.9rem;

  font-weight: 600;
}

.product-compare {
  position: absolute;

  top: 0.5rem;

  right: 0.5rem;

  display: flex;

  align-items: center;

  background-color: #fff;

  border-radius: 4px;

  padding: 8px;

  border: 1px solid #333;

  transition: opacity 0.2s ease-in-out;

  opacity: 0;
}

.card:hover .product-compare {
  opacity: 1;
}

.product-compare:focus-within {
  opacity: 1;
}

.product-compare label {
  font-size: 0.9rem;

  margin-right: 8px;
}

.product-compare input {
  margin: 0 !important;
}

//js

const cards = document.querySelectorAll(".card");
Array.prototype.forEach.call(cards, (card) => {
  let down,
    up,
    link = card.querySelector("h2 a");
  if (link !== null) {
    card.style.cursor = "pointer";
    card.onmousedown = () => (down = +new Date());
    card.onmouseup = (e) => {
      up = +new Date();
      if (up - down < 200 && e.button !== 2) {
        link.click();
      }
    };
  }
});
