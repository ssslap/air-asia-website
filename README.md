# Air Asia Website

Веб-сайт авиакомпании Air Asia, созданный в рамках курса по фронтенд/бэкенд разработке.

## Структура проекта

- `index.html` - главная страница сайта
- `styles.css` - файл стилей
- `README.md` - документация проекта

## Требования к реализации

- ✅ Верстка обернута в блок `.wrapper`
- ✅ Использованы семантические списки (`<ul>`, `<li>`) для повторяющихся элементов
- ✅ Единообразные классы для одинаковых типов элементов
- ✅ Адаптивный дизайн
- ✅ Главная страница названа `index.html`

## Инструкция по развертыванию на GitHub Pages

### 1. Создание репозитория на GitHub

1. Перейдите на [GitHub.com](https://github.com) и войдите в свой аккаунт
2. Нажмите кнопку "+" в правом верхнем углу и выберите "New repository"
3. Заполните информацию:
   - **Repository name**: `air-asia-website`
   - **Description**: `Air Asia airline website implementation`
   - Выберите "Public"
   - НЕ отмечайте "Initialize this repository with a README" (файлы уже созданы)
4. Нажмите "Create repository"

### 2. Загрузка файлов в репозиторий

#### Способ 1: Через веб-интерфейс GitHub
1. В созданном репозитории нажмите "Add file" → "Upload files"
2. Перетащите файлы `index.html`, `styles.css` и `README.md` в область загрузки
3. Нажмите "Commit changes"

#### Способ 2: Через Git командную строку
```bash
# Инициализация Git
git init

# Добавление файлов
git add index.html styles.css README.md

# Коммит изменений
git commit -m "Initial commit: Air Asia website"

# Добавление удаленного репозитория
git remote add origin https://github.com/ВАШ_USERNAME/air-asia-website.git

# Отправка изменений
git branch -M main
git push -u origin main
```

### 3. Настройка GitHub Pages

1. В репозитории перейдите во вкладку "Settings"
2. В левом меню выберите "Pages"
3. В разделе "Branch":
   - Выберите ветку `main` (или `master`)
   - Папку оставьте `/ (root)`
4. Нажмите "Save"
5. Подождите несколько минут пока GitHub развернет сайт

### 4. Доступ к сайту

После настройки GitHub Pages ваш сайт будет доступен по адресу:
```
https://ВАШ_USERNAME.github.io/air-asia-website/
```

Замените `ВАШ_USERNAME` на ваше имя пользователя GitHub.

## Особенности реализации

- Адаптивный дизайн для мобильных устройств
- Семантическая верстка
- Современный CSS с использованием Grid и Flexbox
- Интерактивные элементы с hover-эффектами
- Чистая и понятная структура кода

## Технологии

- HTML5
- CSS3
- Responsive Web Design
- GitHub Pages для хостинга
