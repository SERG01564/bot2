# Telegram WebApp для заявок

Веб-приложение для отправки заявок через Telegram WebApp.

## Технологии

- Next.js 14
- TypeScript
- Tailwind CSS
- Telegram WebApp SDK
- Supabase

## Разработка

1. Установите зависимости:
```bash
npm install
```

2. Создайте файл `.env.local` с переменными окружения:
```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

3. Запустите сервер разработки:
```bash
npm run dev
```

## Деплой на Vercel

1. Создайте аккаунт на [Vercel](https://vercel.com)
2. Подключите ваш GitHub репозиторий
3. Настройте переменные окружения в настройках проекта:
   - `NEXT_PUBLIC_SUPABASE_URL`
   - `NEXT_PUBLIC_SUPABASE_ANON_KEY`
4. Нажмите "Deploy"

## Настройка Telegram Bot

1. Создайте бота через [@BotFather](https://t.me/BotFather)
2. Включите WebApp для бота
3. Установите URL вашего приложения на Vercel в настройках WebApp

## Структура проекта

- `src/app/page.tsx` - главная страница
- `src/components/LeadForm.tsx` - компонент формы заявки
- `vercel.json` - конфигурация для Vercel 