<template>
  <div class="home">
    <header class="header">
      <div class="header__avatar"><img src="" alt="" /></div>
      <div class="header__content">
        <h1>Земляков Константин</h1>
        <p><strong>Web-разработчик</strong></p>
      </div>
    </header>
    <main class="content">
      <p>
        Привет! Меня зовут Земляков Константин, мне 19 лет, живу в Омске, люблю
        программирование и веб-разработку.
      </p>
      <div class="projects">
        <h2 class="projects__title">Проекты:</h2>
        <ul class="projects__list">
          <li>
            <a href="https://github.com/Haliont/brain-games">Набор консольных игр для тренировки мозга</a>
          </li>
          <li>
            <a href="https://github.com/Haliont/diffcalculus">Вычислитель отличий</a>
          </li>
          <li>
            <a href="https://github.com/Haliont/rss-reader">RSS-reader</a>
          </li>
          <li>
            <a href="https://github.com/Haliont/vanila-spa">Совсем простое SPA на VanilaJS</a>
          </li>
          <li>
            <a href="https://github.com/Haliont/fifteen-puzzle">Игра пятнашки</a>
          </li>
          <li><a href="http://love-heart.surge.sh/">Тупо сердце</a></li>
          <li>
            <a
              href="https://github.com/Haliont?utf8=%E2%9C%93&tab=repositories&q=&type=source&language="
            >
              Больше...
            </a>
          </li>
        </ul>
      </div>
      <div class="contacts">
        <h2 class="contacts__title">Контакты:</h2>
        <ul class="contacts__list">
          <li><a href="tel:89333025370">8-933-302-53-70</a></li>
          <li><a href="https://t.me/hahahaliont">Телеграм</a></li>
          <li><a href="https://vk.com/haliont">ВК</a></li>
          <li><a href="https://github.com/Haliont">Гитхаб</a></li>
          <li>
            <a
              href="https://omsk.hh.ru/resume/fcf55312ff05c4f2840039ed1f45613379746c"
            >
              Резюме
            </a>
          </li>
        </ul>
      </div>
    </main>
    <footer class="footer">&copy; 2018, Земляков Константин</footer>
  </div>
</template>

<script>

export default {
  name: 'home',
};

</script>

<style>
  html {
    height: 100%;
  }

  body {
    min-height: 100%;
    font-family: "Montserrat", sans-serif;
    display: flex;
    flex-direction: column;
    max-width: 786px;
    margin: 0 auto;
    padding: 0 15px;
  }

  .home {

  }

  .header,
  .footer {
    padding: 10px 0;
  }

  .header {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
  }

  .header__avatar {
    display: flex;
    align-items: center;
    max-width: 60px;
    margin-right: 10px;
  }

  .header__avatar img {
    max-width: 100%;
    height: auto;
    border-radius: 50%;
  }

  .header__content h1,
  .header__content p {
    margin: 0;
  }

  .header__content strong {
    font-style: italic;
  }

  .content {
    flex-grow: 1;
  }
</style>