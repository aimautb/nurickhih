Cloud Computing шпаргалка — версия для Vercel

Структура проекта:
  vercel.json
  public/index.html

Деплой через Vercel:
1. Создай репозиторий на GitHub.
2. Загрузи в корень репозитория файл vercel.json и папку public.
3. В Vercel выбери Add New → Project и импортируй репозиторий.
4. Framework Preset: Other.
5. Build Command и Install Command оставь пустыми.
6. Output Directory: public.
7. Нажми Deploy.

Файл уже самостоятельный: CSS и JavaScript встроены внутри index.html.
Никакие npm-пакеты или переменные окружения не нужны.

Через терминал:
  cd cloud-computing-cheatsheet-vercel
  npx vercel --prod
