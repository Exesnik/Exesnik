<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Exesnik/Exesnik/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Exesnik/Exesnik/output/github-snake.svg" />
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/Exesnik/Exesnik/output/github-snake-dark.svg" />
  </picture>
</div>

<br/>

<div align="center">
  <h1>Привет! Я Николай Моисеенко 👋</h1>
  <p>
    <a href="https://git.io/typing-svg">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=238636&center=true&vCenter=true&width=580&lines=Unity+%2F+XR+(AR+%26+VR)+Developer;C%23+%7C+OpenXR+%7C+ARFoundation;On-Device+Computer+Vision+(Unity+Sentis);Industrial+Simulators+%26+Mobile+AR" alt="Typing SVG" />
    </a>
  </p>
  <p>
    <a href="https://t.me/HoroshyiChelovechek"><img src="https://img.shields.io/badge/Telegram-@HoroshyiChelovechek-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
    <a href="mailto:exesnik2002@gmail.com"><img src="https://img.shields.io/badge/Gmail-exesnik2002@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
    <a href="https://github.com/Exesnik"><img src="https://img.shields.io/badge/Location-Samara%2C%20Russia-238636?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" /></a>
  </p>
</div>

---

## 🚀 Обо мне

Разработчик интерактивных систем, мобильных AR-приложений и симуляторов виртуальной реальности с опытом коммерческой и исследовательской разработки более **3.5 лет**.

🎓 **Образование:**
- **Магистратура (2024–2026/2027, в процессе написания диссертации):** Самарский государственный технический университет (СамГТУ), Институт автоматики и информационных технологий — *«Программная Инженерия»*.  
  *Тема исследования:* Разработка и интеграция локальных моделей компьютерного зрения (YOLOv8 / ONNX / Unity Sentis) в интерактивные AR-системы.
- **Бакалавриат (2020–2024):** Тольяттинская академия управления (ТАУ) — *«Прикладная информатика (в экономике)»*.  
  *ВКР:* Разработка интерактивного мобильного AR-приложения "Карта Солнечной системы" (Unity, ARFoundation/ARCore).

Подхожу к коду с упором на надежную компонентную архитектуру (ООП, SOLID, Scriptable Objects, JSON-конфигурации), асинхронную логику на Coroutines и DOTween (исключая race conditions) и реальную оптимизацию производительности под мобильные устройства и автономные шлемы.

---

## 🛠 Технологический стек

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=unity,cs,dotnet,androidstudio,py,git,github,vscode" alt="Tech Stack Icons" />
  </a>
</div>

<br/>

### Core & Game Engine
- **Unity:** 2021 LTS, 2022 LTS, Unity 6
- **C# / .NET:** OOP, SOLID, Scriptable Objects, Event System, Coroutines, DOTween, JSON-парсеры
- **UI:** uGUI (Canvas — основной инструмент верстки адаптивных интерфейсов), UI Toolkit
- **Оптимизация:** Профилирование (Unity Profiler), контроль аллокаций памяти (GC Alloc), настройка LOD (уровней детализации), троттлинг кадровой логики в Update

### XR (Дополненная и виртуальная реальность)
- **AR:** ARFoundation, ARCore (Android Plane Detection, Raycasting, Object Tracking, пространственная привязка 3D-моделей)
- **VR:** OpenXR, XR Interaction Toolkit (XRI), AutoHand (физика рук и реалистичные захваты), Meta Quest SDK, Pico XR SDK
- **Эргономика:** World-Space UI, Billboarding, предотвращение Motion Sickness, комфортная локомоция

### Прикладной AI и автоматизация (R&D)
- **Компьютерное зрение:** YOLOv8 (детекция объектов и микроэлектроники), PyTorch, OpenCV, сбор и аннотация датасетов (Roboflow / CVAT)
- **Инференс в Unity:** Unity Sentis, ONNX Runtime (полностью автономный локальный инференс на мобильном устройстве без облачных задержек)
- **MCP & Tooling:** Внедрение и настройка open-source MCP-серверов (unity-mcp, Godot, DaVinci Resolve) для подключения LLM-агентов к Unity Editor и автоматизации сборки сцен

---

## 📌 Ключевые проекты (Featured Repositories)

| Проект | Платформа / Стек | Ключевые инженерные решения | Исходный код |
|:---|:---|:---|:---:|
| 🛩️ **[AR Drone Trainer](https://github.com/Exesnik/ar-drone-soldering-trainer)** | Android<br/>Unity Sentis<br/>YOLOv8 | • On-device GPU инференс (Unity Sentis)<br/>• Per-Class Peak Confidence NMS-фильтр<br/>• FSM сценария пайки на корутинах | [![Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/Exesnik/ar-drone-soldering-trainer) |
| 🪐 **[Solar System AR](https://github.com/Exesnik/solar-system-ar-app)** | Android<br/>ARFoundation<br/>ARCore | • Детекция горизонтальных плоскостей<br/>• Процедурные орбиты с `lossyScale` учетом<br/>• DOTween анимации и инфо-карточки | [![Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/Exesnik/solar-system-ar-app) |
| 🥽 **[VR Mechanics Kit](https://github.com/Exesnik/vr-mechanics-interaction-kit)** | Meta Quest, Pico<br/>OpenXR<br/>PhysX | • Адаптер хвата с оффсетом `_primaryGrabPoint`<br/>• `MovePosition` / `MoveRotation` в FixedUpdate<br/>• Динамический LOD под автономные VR-шлемы | [![Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/Exesnik/vr-mechanics-interaction-kit) |

---

## 📊 Используемые языки

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Exesnik&layout=compact&theme=github_dark&hide_border=true&title_color=238636&text_color=c9d1d9&bg_color=0d1117" alt="Top Languages" />
</div>

---

## 📫 Контакты
- **Telegram:** [@HoroshyiChelovechek](https://t.me/HoroshyiChelovechek)
- **Email:** [exesnik2002@gmail.com](mailto:exesnik2002@gmail.com)
- **Локация:** Самара (Офис / Гибрид / Удаленная работа / Готов к переезду и командировкам)
