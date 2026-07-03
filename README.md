# LNTU Specialty Picker

Готовий статичний сайт для Render.  
Основний файл сайту: `index.html`.

## Як залити на GitHub

### Варіант 1 — через сайт GitHub
1. Створи новий репозиторій на GitHub.
2. Натисни **Add file → Upload files**.
3. Перетягни файли з цієї папки:
   - `index.html`
   - `render.yaml`
   - `README.md`
   - `lntu_specialty_picker_edbo.py` — необов'язково, це консольна Python-версія.
4. Натисни **Commit changes**.

### Варіант 2 — через Git
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/lntu-specialty-picker.git
git push -u origin main
```

## Як запустити на Render

1. Зайди на Render.
2. Натисни **New +**.
3. Обери **Static Site** або **Blueprint**, якщо Render сам побачить `render.yaml`.
4. Підключи свій GitHub-репозиторій.
5. Якщо обираєш Static Site вручну:
   - **Build Command**: залиш порожнім
   - **Publish Directory**: `.`
6. Натисни **Deploy Static Site**.

Після деплою Render дасть посилання типу:
`https://lntu-specialty-picker.onrender.com`

## Локальний запуск

Просто відкрий `index.html` у браузері.
