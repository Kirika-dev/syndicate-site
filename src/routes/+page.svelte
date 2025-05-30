<script>
  import Header from '../components/Header.svelte';
  import LiveStreams from '../components/LiveStreams.svelte';
  import OnceHumanSection from '../components/OnceHumanSection.svelte';
  </script>

<Header />
<main>
  <h1>Добро пожаловать в SYNDICATE</h1>
  <p>Объединение стримеров, геймеров и контент-мейкеров.</p>

  <LiveStreams />

  <OnceHumanSection />
  <section id="schedule">
    <h2>Расписание</h2>
    <p>Скоро будет доступно.</p>
  </section>
  <section id="news">
    <h2>Новости</h2>
    <p>Следите за нашими обновлениями в Discord.</p>
  </section>
  <section id="gallery">
    <h2>Галерея</h2>
    <p>Скоро будет доступно.</p>
  </section>
  <section id="forum">
    <h2>Форум</h2>
    <p>Скоро будет доступно.</p>
  </section>
  <section id="chat">
    <h2>Чат</h2>
    <p>Присоединяйтесь к нашему Discord для общения.</p>
  </section>
  <section id="contact">
    <h2>Контакты</h2>
<p>Для сотрудничества и вопросов пишите на почту: <a href="mailto:info@syndicate.com">info@syndicate.com</a>.</p>
  </section>
</main>