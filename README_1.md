# 𝄞 Fortelia

**[Русский](#русский) · [English](#english)**

---

## Русский

**Fortelia** — бесплатный тренажёр для игры на пианино прямо в браузере. Падающие неоновые ноты, нотный стан, уроки аккордов, классические пьесы и теория музыки с нуля. Работает с обычной клавиатурой компьютера и с электронным пианино по MIDI. Игра на акустическом пианино через микрофон — **скоро**.

Без подписок, без регистрации, без интернета. Всё приложение — один HTML-файл.

![Fortelia](screenshots/home.png)

### Возможности

**Тренажёр**
- Падающие ноты-полоски с неоновым свечением, несколько тем и цветов.
- Режим «Ждать ноту»: песня стоит, пока ты не нажмёшь правильную клавишу. Ошибки подсвечиваются.
- Названия нот (C D E…) на полосках и клавишах.
- Нотный стан строится автоматически из MIDI: отдельной панелью или фоном.
- Отдельно правая рука, левая или обе. Регулировка темпа, петля, отсчёт 3-2-1.
- Звук песни можно сделать тише своей игры, чтобы слышать себя.

**Три способа играть**
- **Клавиатура компьютера.** Q — нота C выбранной октавы, ряд Z — октавой ниже. Можно нажимать клавиши мышкой.
- **Электронное пианино по USB (MIDI).**

**Звук**
- Настоящий концертный рояль (семплы Salamander Grand Piano) с резонансом корпуса и лёгким эхом зала.

**3D, видео и запись**
- **3D-вид:** рояль на сцене под прожектором, неоновые ноты падают на клавиши, светящиеся руки играют. Ракурсы: клавиши, сцена, пианист, сбоку, облёт, авто.
- **Режим видео:** вертикальный 9:16 для Reels, TikTok и Shorts, 16:9 для YouTube или 1:1. Название в начале, подпись сайта, запись ролика со звуком в один клик.
- **Запись игры:** нажми «⏺ Запись» и играй на клавиатуре или MIDI-пианино. Приложение превратит игру в мелодию с падающими нотами и сохранит её как MIDI-файл.

**Сайт целиком**
- **Уроки:** 21 урок, от «найди ноту C» до гамм, аккордов и популярных последовательностей.
- **Классика:** 22 пьесы в простой аранжировке и 18 полных оригинальных версий (Бах, Моцарт, Бетховен, Шопен, Дебюсси, Джоплин и другие): Бах, Моцарт, Бетховен, Чайковский, Григ, народные песни, джаз и блюз. Фильтры по жанру и сложности, сортировка, поиск.
- **Теория:** 18 статей в трёх уровнях: клавиатура, ритм, ноты, интервалы, аккорды, тональности, интерактивный квинтовый круг, педаль и советы по занятиям.
- **Моя библиотека:** открытые MIDI-файлы хранятся только в твоём браузере и никуда не отправляются.
- Два языка: русский и английский.

### Как запустить

1. Скачай `Fortelia.html`.
2. Открой его в **Chrome** или **Edge** (в других браузерах MIDI может не работать).
3. Готово. Интернет не нужен.


### Свои песни

Fortelia не содержит лицензионных песен. Загружай свои MIDI-файлы: сыгранные тобой, купленные или из свободных источников (например, произведения в общественном достоянии). Файлы остаются на твоём компьютере.

### Конфиденциальность

Приложение ничего не отправляет в интернет. Настройки, прогресс и библиотека хранятся в `localStorage` и `IndexedDB` твоего браузера.

### Скоро

- **Игра через микрофон** на обычном акустическом пианино. Режим уже есть в приложении, но выключен, пока мы доводим точность распознавания.
- **Рейтинг и аккаунты:** рейтинговые игры, таблицы лидеров, статистика.
- **Баттлы** на 30 секунд, 1 и 5 минут: очки за точность, комбо и темп. Боты разной силы и баттлы по своему MIDI-файлу.
- **Выступления в 3D-зале** для друзей и кооператив на двоих.
- **VR-режим** прямо в браузере.

### Благодарности и лицензии

- **Звук рояля:** [Salamander Grand Piano](https://archive.org/details/SalamanderGrandPianoV3) — автор **Alexander Holm**, лицензия [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Используется набор семплов, подготовленный проектом [Tone.js](https://github.com/Tonejs/audio). Семплы сжаты и встроены в файл.
- **Мелодии** в разделах «Классика» и «Уроки» — произведения в общественном достоянии и народные песни в собственных простых аранжировках, плюс оригинальные упражнения.
- **3D-графика:** [three.js](https://threejs.org), лицензия MIT.
- **Модели рук:** [WebXR Input Profiles](https://github.com/immersive-web/webxr-input-profiles) (generic-hand), © Amazon, лицензия MIT.
- **Полные версии классики:** ноты из [Mutopia Project](https://www.mutopiaproject.org), переведены в MIDI. Большинство — общественное достояние. «Лунная соната» (набор: Stewart Holmes, CC BY-SA 2.5), Соната K545 (Alejandro Sierra, CC BY-SA 3.0), Инвенция №1 (jeff covey, CC BY-SA 3.0) и «Утешение №3» Листа (Ryan Prince, CC BY 3.0) распространяются на условиях этих лицензий. Имя наборщика указано на карточке каждой пьесы.
- **Код приложения:** лицензия MIT (см. `LICENSE`).

---

## English

**Fortelia** is a free piano trainer that runs right in your browser. Falling neon notes, sheet music, chord lessons, classical pieces and music theory from scratch. It works with your computer keyboard and a digital piano over MIDI. Playing an acoustic piano through the microphone is **coming soon**.

No subscriptions, no sign-up, no internet. The whole app is a single HTML file.

![Fortelia](screenshots/home_en.png)

### Features

**Trainer**
- Falling note bars with a neon glow, several themes and colours.
- “Wait for note” mode: the song pauses until you hit the right key. Wrong notes are highlighted.
- Note names (C D E…) on bars and keys.
- Sheet music generated automatically from MIDI, as a panel or as a background.
- Right hand, left hand or both. Tempo control, loop, 3-2-1 count-in.
- The song's own sound can play quieter than you, so you hear yourself.

**Three ways to play**
- **Computer keyboard.** Q is C of the selected octave, the Z row is an octave lower. You can also click keys with the mouse.
- **Digital piano over USB (MIDI).**

**Sound**
- A real concert grand (Salamander Grand Piano samples) with soundboard resonance and a light hall echo.

**3D, video and recording**
- **3D view:** a grand piano on a spotlit stage, neon notes falling onto the keys, glowing hands playing. Cameras: keys, stage, pianist, side, fly-around, auto.
- **Video mode:** vertical 9:16 for Reels, TikTok and Shorts, 16:9 for YouTube, or 1:1. Title card, site caption, one-click recording with sound.
- **Record your playing:** press “⏺ Record” and play on the computer keyboard or a MIDI piano. The app turns it into a falling-notes song and saves it as a MIDI file.

**A full site**
- **Lessons:** 21 lessons, from “find the note C” to scales, chords and popular progressions.
- **Classics:** 22 pieces in simple arrangements and 18 full original versions (Bach, Mozart, Beethoven, Chopin, Debussy, Joplin and more): Bach, Mozart, Beethoven, Tchaikovsky, Grieg, folk songs, jazz and blues. Genre and difficulty filters, sorting, search.
- **Theory:** 18 articles in three levels: the keyboard, rhythm, reading notes, intervals, chords, keys, an interactive circle of fifths, the pedal and practice tips.
- **My library:** MIDI files you open are stored only in your browser and never uploaded.
- Two languages: Russian and English.

### How to run

1. Download `Fortelia.html`.
2. Open it in **Chrome** or **Edge** (MIDI may not work in other browsers).
3. That's it. No internet needed.


### Your own songs

Fortelia ships with no licensed songs. Load your own MIDI files: ones you recorded, bought, or got from free sources (for example, public-domain works). Files stay on your computer.

### Privacy

The app sends nothing to the internet. Settings, progress and your library live in your browser's `localStorage` and `IndexedDB`.

### Coming soon

- **Microphone play** on a regular acoustic piano. The mode is already in the app but switched off while we improve recognition accuracy.
- **Ratings and accounts:** ranked games, leaderboards, statistics.
- **Battles** of 30 seconds, 1 and 5 minutes: points for accuracy, combos and tempo. Bots of different strength and battles on your own MIDI file.
- **Performances in a 3D concert hall** for friends, and two-player co-op.
- **VR mode** right in the browser.

### Credits and licences

- **Piano sound:** [Salamander Grand Piano](https://archive.org/details/SalamanderGrandPianoV3) by **Alexander Holm**, licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Uses the sample set prepared by the [Tone.js](https://github.com/Tonejs/audio) project. The samples are compressed and embedded in the file.
- **Melodies** in Classics and Lessons are public-domain works and folk songs in original simple arrangements, plus original exercises.
- **3D graphics:** [three.js](https://threejs.org), MIT licence.
- **Hand models:** [WebXR Input Profiles](https://github.com/immersive-web/webxr-input-profiles) (generic-hand), © Amazon, MIT licence.
- **Full classical versions:** scores from the [Mutopia Project](https://www.mutopiaproject.org), converted to MIDI. Most are public domain. The Moonlight Sonata (typeset by Stewart Holmes, CC BY-SA 2.5), Sonata K545 (Alejandro Sierra, CC BY-SA 3.0), Invention No. 1 (jeff covey, CC BY-SA 3.0) and Liszt's Consolation No. 3 (Ryan Prince, CC BY 3.0) are shared under those licences. Each piece's card names its typesetter.
- **App code:** MIT licence (see `LICENSE`).
