<div align="center">

<!-- HEADER: PURPLE NEON STYLE -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:240046,100:7B2CBF&height=220&section=header&text=CARDORA%20AI&fontSize=90&animation=fadeIn&fontColor=E0AAFF&desc=ENTERPRISE%20CONTENT%20AUTOMATION&descAlign=62&descAlignV=72" width="100%" style="border-radius: 24px;" />

<br>

<!-- TYPING TEXT -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=600&size=22&duration=3000&pause=1000&color=C77dff&center=true&vCenter=true&width=700&height=50&lines=Neural+Upscaling+System+(4K);Photoshop+Direct+Injection;Smart+Excel+Data+Hub;Zero-Touch+Automation" alt="Typing SVG" />
</a>

<p style="color: #E0AAFF; font-size: 18px; margin-top: 10px; font-weight: 500;">
    Промышленный стандарт автоматизации для селлеров Wildberries и Ozon
</p>

<!-- BADGES -->
<p>
    <img src="https://img.shields.io/badge/Release-v1.0.0-7B2CBF?style=for-the-badge&labelColor=240046">
    <img src="https://img.shields.io/badge/OS-Windows_10_/_11-0078D4?style=for-the-badge&logo=windows">
    <img src="https://img.shields.io/badge/Wildberries-Ready-purple?style=for-the-badge&logo=shopee">
    <img src="https://img.shields.io/badge/Ozon-Ready-blue?style=for-the-badge&logo=azure-devops">
    <img src="https://img.shields.io/badge/Качество-AI%204K-success?style=for-the-badge">
</p>

<br>
</div>

## 🛸 О Проекте | The Mission

**Cardora AI** — это не просто редактор, это автономная рабочая станция, заменяющая целый отдел контента.
Мы объединили **нейросети (Computer Vision)**, **промышленную автоматизацию Photoshop** и **работу с данными (Excel)** в единый конвейер.

> **Ваша выгода:** Вы загружаете папку с "сырыми" фото — через 5 минут получаете готовые карточки и заполненную спецификацию для загрузки на маркетплейс.

---

## 📺 Демонстрация работы

Посмотрите, как Cardora обрабатывает реальный кейс за 60 секунд.

<div align="center">
  <!-- ПРЕВЬЮ ВИДЕО -->
  <!-- Загрузи скриншот видео в папку assets и назови video_preview.jpg -->
  <a href="ССЫЛКА_НА_ВИДЕО_ВК">
    <img src="assets/video_preview.jpg" width="100%" style="border-radius: 12px; border: 2px solid #7B2CBF; box-shadow: 0 0 20px rgba(123, 44, 191, 0.3);" alt="Нажмите для просмотра видео">
  </a>
  
  <br>
  
  <!-- КНОПКИ ВЫБОРА ПЛАТФОРМЫ -->
  <a href="ССЫЛКА_НА_ВИДЕО_ВК">
    <img src="https://img.shields.io/badge/Смотреть_на-VK_Video-0077FF?style=for-the-badge&logo=vk&logoColor=white">
  </a>
  &nbsp;&nbsp;
  <a href="ССЫЛКА_НА_ЮТУБ">
    <img src="https://img.shields.io/badge/Смотреть_на-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
  </a>
</div>

---

## ⚡ Функциональные модули

### 1. 🧠 Центр Генерации (AI Core)
Сердце системы. Здесь происходит магия улучшения качества.
*   **Умный Апскейл:** Если фото плохого качества, нейросеть (Real-ESRGAN) достраивает пиксели, превращая размытое изображение в четкое 4K.
*   **Smart Skip:** Если фото уже качественное (>1500px), система пропускает тяжелую обработку, экономя время.
*   **Защита железа:** Алгоритм тайлинга и пауз защищает ваш ПК от перегрева даже при обработке 1000 товаров.

<div align="center">
  <img src="assets/generic_window.png" width="90%" style="border-radius: 10px; border: 1px solid #5a189a;">
</div>

<br>

### 2. 📂 Менеджер Ресурсов (Smart Linking)
Забудьте о путанице в файлах.
*   **Связи:** Вы один раз указываете, какой PSD-макет подходит к какой таблице Excel.

<div align="center">
  <img src="assets/file_window.png" width="90%" style="border-radius: 10px; border: 1px solid #5a189a;">
</div>

<br>

### 3. 📊 Конфигуратор Данных (Excel Hub)
Автоматическое заполнение спецификаций для Wildberries/Ozon.
*   **Без ошибок:** Программа сама вписывает артикулы сгенерированных фото в таблицу.
*   **Шаблонизация:** Настройте бренд, цену и описание один раз — они автоматически продублируются для всех товаров в партии.

<div align="center">
  <img src="assets/table_window.png" width="90%" style="border-radius: 10px; border: 1px solid #5a189a;">
</div>

---

<!-- СЕКЦИЯ ДЛЯ РАЗРАБОТЧИКОВ (СПОЙЛЕР) -->
<details>
<summary><h2>🛠️ Engineering Deep Dive (Архитектура и Стек)</h2></summary>
<br>
Этот раздел предназначен для технических специалистов и HR, желающих понять внутреннее устройство системы.

### 🏗️ Core & Architecture
*   **Language:** Python 3.12 (LTS Stability).
*   **UI Framework:** PySide6 (Qt6) + Fluent Design System (Acrylic/Mica effects).
*   **Build System:** Проект скомпилирован в машинный код через **Nuitka** (Standalone Mode), что обеспечивает производительность C++ и защиту исходников.

### 🧠 Computer Vision & AI
*   **Engine:** Real-ESRGAN (Vulkan/ncnn implementation) для GPU-ускорения.
*   **Processing:** Pillow (PIL) для пре-процессинга, геометрических трансформаций и анализа метаданных.
*   **Optimization:** Реализован алгоритм **Tiling** (сегментация) для обработки 4K изображений на видеокартах с малым объемом VRAM.

### 🎨 Automation & Data Logic
*   **Photoshop Bridge:** Собственная реализация COM-интерфейса (Dynamic JSX Injection).
*   **Data Engine:** OpenPyXL для сложного парсинга и генерации Excel-отчетов.
*   **Persistence:** Локальная JSON-база данных для хранения связей и настроек сессий.

### 🛡️ Security & Enterprise Features
*   **Hardware Fingerprinting:** Генерация уникального HWID на основе серийных номеров CPU и Disk Drive (WMI Requests).
*   **Cloud Control:** Система удаленной проверки лицензий.
*   **Anti-Tamper:** Бинарная защита исполняемого файла от реверс-инжиниринга.

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,qt,pytorch,opencv,ps&theme=dark" />
</div>
</details>
<!-- КОНЕЦ СЕКЦИИ ДЛЯ РАЗРАБОТЧИКОВ -->

---

## 📥 Как начать работу?

1.  Перейдите во вкладку [**Releases (Скачать)**](../../releases).
2.  Загрузите файл `CardoraStudio_v1.0_Setup.exe`.
3.  Установите программу (Инсталлятор сам настроит все драйверы Visual C++).
4.  При запуске скопируйте ваш **Hardware ID**.

---

## 📞 Контакты и Приобретение

Готовы ускорить работу в 10 раз? Свяжитесь с нами для получения демо-ключа или покупки полной версии.

<div align="center">
  <a href="https://t.me/igalaxyLight">
    <img src="https://img.shields.io/badge/Telegram-Написать-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&height=40">
  </a>
</div>

<br><br>

<div align="center">
    <p style="color: #9d4edd; font-size: 12px; letter-spacing: 2px;">
    DEVELOPED BY YGALAXYY • 2026<br>
    POWERED BY NEURAL NETWORKS
    </p>
</div>
