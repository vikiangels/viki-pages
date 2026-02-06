---
<header class="hero">
  <div class="hero-card">
    <p class="badge">☀️ Тут всегда солнечно</p>
    <h1>Как здорово, что вы здесь!</h1>
    <p class="subtitle">
      Добро пожаловать на мою личную страницу. Здесь я делюсь идеями и помогаю решать важные вопросы в Германии.
    </p>
    <div class="chips">
      <span>Детский сад</span>
      <span>Документы</span>
      <span>Jobcenter</span>
      <span>Переводы</span>
      <span>Жильё</span>
    </div>
  </div>
</header>

<section class="section">
  <h2>👋 Обо мне</h2>
  <div class="card">
    <p>
      Привет, меня зовут <strong>Вики</strong>. Я помощница и энтузиастка.
      На этом сайте вы найдёте информацию о моих услугах и интересах.
    </p>
  </div>
</section>

<section class="section">
  <h2>🧩 Чем я могу помочь</h2>

  <div class="grid">
    <div class="service">
      <h3>📑 Детские садики</h3>
      <p><strong>Подача заявлений</strong> и оформление документов для получения места.</p>
      <p class="tags"><span>#Kita</span><span>#Antrag</span><span>#Документы</span></p>
    </div>

    <div class="service">
      <h3>🩺 Врачи (Charité и др.)</h3>
      <p>Сопровождение и помощь с <strong>медицинскими документами</strong>.</p>
      <p class="tags"><span>#Doctor</span><span>#Charité</span><span>#Перевод</span></p>
    </div>

    <div class="service">
      <h3>✍️ WBS / соц. жильё</h3>
      <p>Помощь в оформлении <strong>WBS</strong> и документов для социального жилья.</p>
      <p class="tags"><span>#WBS</span><span>#Wohnung</span><span>#Berlin</span></p>
    </div>

    <div class="service">
      <h3>📝 ВНЖ / §24</h3>
      <p>Подготовка документов для <strong>ВНЖ</strong>, <strong>§24</strong> и сопровождение.</p>
      <p class="tags"><span>#Aufenthalt</span><span>#§24</span><span>#Документы</span></p>
    </div>

    <div class="service">
      <h3>🗣️ Переводчик</h3>
      <p>Перевод и помощь при общении с <strong>гос. органами</strong> и учреждениями.</p>
      <p class="tags"><span>#Übersetzung</span><span>#Behörden</span></p>
    </div>

    <div class="service">
      <h3>📖 Jobcenter / Arbeitsagentur</h3>
      <p>Регистрация, заявления и сопровождение в <strong>Jobcenter</strong> и <strong>Arbeitsagentur</strong>.</p>
      <p class="tags"><span>#Jobcenter</span><span>#Arbeit</span><span>#Anträge</span></p>
    </div>

    <div class="service">
      <h3>💼 Резюме и работа</h3>
      <p><strong>CV</strong>, подготовка к собеседованию, поиск вакансий, профиль на платформах.</p>
      <p class="tags"><span>#CV</span><span>#Interview</span><span>#Jobs</span></p>
    </div>

    <div class="service">
      <h3>🏥 Медстраховка</h3>
      <p>Выбор <strong>gesetzlich / privat</strong>, регистрация в системе здравоохранения.</p>
      <p class="tags"><span>#KV</span><span>#Versicherung</span></p>
    </div>

    <div class="service">
      <h3>💳 Банковский счёт</h3>
      <p>Открытие счёта, выбор банка и сопровождение на встречу.</p>
      <p class="tags"><span>#Bank</span><span>#Konto</span></p>
    </div>

    <div class="service">
      <h3>🏠 Поиск жилья</h3>
      <p>Сопровождение в поиске, переговоры с арендодателями, пакет документов.</p>
      <p class="tags"><span>#Wohnung</span><span>#Miete</span><span>#Unterlagen</span></p>
    </div>

    <div class="service">
      <h3>📋 Anmeldung / Bürgeramt</h3>
      <p>Подготовка документов и помощь при <strong>Anmeldung</strong>.</p>
      <p class="tags"><span>#Bürgeramt</span><span>#Anmeldung</span></p>
    </div>

    <div class="service">
      <h3>🛡️ Страховки</h3>
      <p>Консультации по оформлению: здоровье, жизнь, имущество и др.</p>
      <p class="tags"><span>#Versicherung</span><span>#Schutz</span></p>
    </div>
  </div>
</section>

<footer class="footer">
  <div class="footer-card">
    <h2>📩 Контакты</h2>
    <p>Напишите мне, и я отвечу с подробностями и свободным временем.</p>
    <p class="small">*Всё обсуждается индивидуально. Конфиденциальность соблюдаю.*</p>
  </div>
</footer>

<style>
  :root{
    --bg: #0b1220;
    --card: rgba(255,255,255,.06);
    --card2: rgba(255,255,255,.08);
    --text: #e8eefc;
    --muted: rgba(232,238,252,.75);
    --accent: #7c4dff;
    --accent2:#22c55e;
    --line: rgba(255,255,255,.12);
  }

  body{ background: var(--bg); color: var(--text); }
  a{ color: #93c5fd; }

  .hero{
    padding: 28px 0 10px;
  }
  .hero-card{
    border: 1px solid var(--line);
    background: linear-gradient(135deg, rgba(124,77,255,.22), rgba(34,197,94,.14));
    border-radius: 18px;
    padding: 22px;
  }
  .badge{
    display:inline-block;
    background: rgba(255,255,255,.12);
    padding: 6px 10px;
    border-radius: 999px;
    font-size: 13px;
    margin-bottom: 10px;
  }
  h1{ margin: 6px 0 10px; font-size: 30px; }
  .subtitle{ color: var(--muted); font-size: 16px; line-height: 1.5; }

  .chips{ margin-top: 12px; display:flex; flex-wrap:wrap; gap:8px; }
  .chips span{
    border: 1px solid var(--line);
    background: rgba(255,255,255,.06);
    padding: 6px 10px;
    border-radius: 999px;
    font-size: 12px;
    color: var(--muted);
  }

  .section{ margin-top: 22px; }
  .card{
    border: 1px solid var(--line);
    background: var(--card);
    border-radius: 16px;
    padding: 16px;
  }

  .grid{
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 12px;
    margin-top: 12px;
  }
  .service{
    border: 1px solid var(--line);
    background: var(--card);
    border-radius: 16px;
    padding: 14px;
    transition: transform .15s ease, background .15s ease;
  }
  .service:hover{
    transform: translateY(-2px);
    background: var(--card2);
  }
  .service h3{ margin: 0 0 8px; font-size: 16px; }
  .service p{ margin: 0 0 8px; color: var(--muted); line-height: 1.45; }
  .service strong{ color: #ffffff; }

  .tags{ display:flex; flex-wrap:wrap; gap:6px; margin-top: 10px; }
  .tags span{
    background: rgba(124,77,255,.18);
    border: 1px solid rgba(124,77,255,.35);
    color: #dcd2ff;
    padding: 4px 8px;
    border-radius: 999px;
    font-size: 11px;
  }

  .footer{ margin: 26px 0 12px; }
  .footer-card{
    border: 1px solid var(--line);
    background: linear-gradient(135deg, rgba(34,197,94,.16), rgba(124,77,255,.12));
    border-radius: 18px;
    padding: 18px;
  }
  .small{ color: var(--muted); font-size: 12px; margin-top: 8px; }
</style>
