# 📄 Web Developers Landing Page - Документація

## 📋 Опис проєкту

Адаптивний односторінковий сайт для веб-студії на основі макету Figma з використанням HTML, SCSS та адаптивного дизайну.

---

## 🏗️ Структура файлів

```
FINAL-PROJECT/
├── css/
│   └── style.css
├── images/
│   └── [фонові зображення]
├── posts_img/
│   └── [зображення постів]
├── scss/
│   ├── _common.scss
│   ├── _variables.scss
│   ├── _mixins.scss
│   ├── _normalize.scss
│   ├── _header.scss
│   ├── _skills.scss
│   ├── _ready.scss
│   ├── _subscribe.scss
│   ├── _posts.scss
│   ├── _footer.scss
│   └── style.scss
└── index.html
```

---

## 🎨 Особливості реалізації

- **SCSS модульна архітектура** з окремими файлами для кожної секції
- **BEM методологія** для іменування класів
- **CSS Grid + Flexbox** для складних макетів
- **Адаптивний дизайн**: Desktop (1300px+), Tablet (768-992px), Mobile (< 768px)
- **Hover-ефекти** на кнопках та карточках
- **Змінні SCSS** для кольорів та шрифтів

---

## 🚀 Інструкції для запуску

### 1. Встановлення Sass

```bash
npm install -g sass
```

### 2. Компіляція SCSS

```bash
# Одноразова компіляція
sass scss/style.scss css/style.css

# Watch mode (автокомпіляція)
sass --watch scss/style.scss:css/style.css
```

### 3. Запуск проєкту

Відкрийте `index.html` у браузері або використайте Live Server.

---

## 🎯 Основні секції

1. **Header** - навігація + hero-секція з фоном
2. **Skills** - Grid-сітка з 9 карточками навичок
3. **Are You Ready** - текст + зображення з роздільною лінією
4. **Subscribe** - форма підписки (3 поля)
5. **Posts** - Grid-сітка з 6 постами
6. **Footer** - центрований контент

---

## 🛠️ Технології

- HTML5 (семантична розмітка)
- SCSS/Sass
- CSS Grid + Flexbox
- Google Fonts (Roboto, Roboto Slab)
- BEM методологія

---

## 📱 Breakpoints

```scss
Desktop:  1300px+
Laptop:   992px - 1300px
Tablet:   768px - 992px
Mobile:   < 768px
```

---

## 🎨 Кольорова палітра

```scss
$color-primaty: #2d3651; // Темно-синій
$color-accent-primary: #d66926; // Оранжевий
$color-accent-secondary: #d53d27; // Червоний
$color-text-main: #637588; // Сірий
```

---

## ✅ Тестування

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Desktop (1920px, 1440px, 1366px)
- ✅ Tablet (768px, 992px)
- ✅ Mobile (375px, 414px, 320px)

---

## 📝 Автор - Гриневич Микола

Фінальний проєкт з верстки | 2025
