# Варианты Support URL без собственного сайта

## Рекомендуемые варианты (бесплатные)

### 1. GitHub Pages (Рекомендуется) ⭐

**Преимущества:**
- Бесплатно
- Профессионально выглядит
- Надежный хостинг от GitHub
- Легко обновлять

**Как создать:**

1. Создайте репозиторий на GitHub:
   ```bash
   # Создайте новый репозиторий на github.com
   # Название: smoke-timer-support (или любое другое)
   ```

2. Загрузите файл `support.html`:
   ```bash
   git init
   git add support.html
   git commit -m "Add support page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/smoke-timer-support.git
   git push -u origin main
   ```

3. Включите GitHub Pages:
   - Перейдите в Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Save

4. Ваш URL будет:
   ```
   https://YOUR_USERNAME.github.io/smoke-timer-support/
   ```

**Пример:** `https://sqrt42.github.io/smoke-timer-support/`

---

### 2. Netlify Drop (Самый простой) ⭐

**Преимущества:**
- Очень просто (перетащить и готово)
- Бесплатно
- Автоматический HTTPS
- Можно подключить кастомный домен

**Как создать:**

1. Перейдите на [netlify.com/drop](https://app.netlify.com/drop)
2. Перетащите папку с файлом `support.html`
3. Получите URL вида: `https://random-name-123.netlify.app`
4. Можно переименовать в настройках

**Пример:** `https://smoke-timer-support.netlify.app`

---

### 3. Vercel (Альтернатива Netlify)

**Преимущества:**
- Бесплатно
- Быстро
- Профессионально

**Как создать:**

1. Установите Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Запустите:
   ```bash
   vercel
   ```

3. Следуйте инструкциям

**Пример:** `https://smoke-timer-support.vercel.app`

---

### 4. GitHub Gist (Минималистичный вариант)

**Преимущества:**
- Очень просто
- Не требует настройки

**Как создать:**

1. Перейдите на [gist.github.com](https://gist.github.com)
2. Создайте новый gist с именем `support.html`
3. Вставьте содержимое файла `support.html`
4. Нажмите "Create public gist"
5. Используйте Raw URL:
   ```
   https://gist.githubusercontent.com/YOUR_USERNAME/GIST_ID/raw/support.html
   ```

**Минусы:** Менее профессионально выглядит, но работает

---

### 5. Google Sites (Простой вариант)

**Преимущества:**
- Очень просто
- Не требует технических знаний

**Как создать:**

1. Перейдите на [sites.google.com](https://sites.google.com)
2. Создайте новый сайт
3. Добавьте информацию о поддержке
4. Опубликуйте
5. Получите URL вида: `https://sites.google.com/view/smoke-timer-support`

---

## Что указать в App Store Connect

### Support URL
Используйте один из вариантов выше, например:
```
https://sqrt42.github.io/smoke-timer-support/
```

### Marketing URL (опционально)
Можно оставить пустым или использовать тот же URL

---

## Минимальная страница поддержки

Если нужна очень простая страница, можно использовать такой минимальный вариант:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Smoke Timer - Support</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body style="font-family: Arial, sans-serif; max-width: 600px; margin: 50px auto; padding: 20px;">
    <h1>Smoke Timer - Support</h1>
    <p>For support, please contact: <a href="mailto:support@smoketimer.app">support@smoketimer.app</a></p>
    <h2>Privacy Policy</h2>
    <p>Smoke Timer stores all data locally on your device. We do not collect or share any personal information.</p>
</body>
</html>
```

---

## Рекомендация

**Лучший вариант:** GitHub Pages
- Профессионально
- Бесплатно
- Надежно
- Легко обновлять

**Самый быстрый:** Netlify Drop
- Перетащил файл → получил URL
- Готово за 2 минуты

---

## Важные замечания

1. **Email для поддержки:** Убедитесь, что email адрес работает и вы будете проверять его регулярно
2. **Privacy Policy:** Обязательно включите информацию о конфиденциальности на странице поддержки
3. **Обновления:** Регулярно обновляйте страницу поддержки при изменении приложения

---

## Пример готового Support URL

После создания страницы на GitHub Pages, ваш Support URL будет выглядеть так:

```
https://sqrt42.github.io/smoke-timer-support/
```

Этот URL можно использовать в App Store Connect как Support URL и Marketing URL.
