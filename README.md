# Wedding — Denis & Karina · 28.08.2026

## URLs

| URL | Описание |
|-----|----------|
| https://wedding-denis-and-karina.vercel.app | Основной адрес (алиас) |
| https://weding-mu.vercel.app | Авто-алиас продакшна (Vercel) |
| https://wedding-dennis-nsts-projects.vercel.app | Алиас по имени проекта/команды |

## Обновление алиасов

После каждого `vercel --prod` алиас `wedding-denis-and-karina.vercel.app` нужно переназначить вручную:

```bash
vercel alias set weding-mu.vercel.app wedding-denis-and-karina.vercel.app
```
