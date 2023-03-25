This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


## Commit policy

```markdown
<**commit type**>(<**optional description**>): <**subject**>
empty line
<optional body>
```

### Type

- Изменения, связанные с кодовой базой
    - `feature` Коммиты, которые добавляют новую функциональность
    - `fix` Коммиты, которые исправляют ошибку
- `refactor` Коммиты, которые переписывают/перестраивают код, не меняя при этом поведение
    - `performance` Коммиты-исключения, которые улучшают производительность
- `style` Коммиты, которые не влияют на смысл (пробелы, форматирование, отсутствующие точки с запятой и т. д.)
- `test` Коммиты, которые добавляют отсутствующие тесты или корректируют существующие
- `docs` Коммиты, которые затрагивают только документацию
- `build` Коммиты, которые затрагивают компоненты сборки, такие как инструменты сборки, ci-пайплайн, зависимости, версии проекта и т. д.
- `ops` Коммиты, которые затрагивают операционные компоненты, такие как инфраструктура, развертывание, резервное копирование, восстановление и т. д.
- `chore` Различные коммиты, которые нельзя отнести к другим категориям например, изменение `.gitignore`

### Subject

`Краткое описание` содержит краткое описание изменений.

- Является **обязательной** частью формата
- Используйте повелительное наклонение, настоящее время: "change" вместо "changed" или "changes"
- Не используйте заглавную букву в начале
- Нет точки (.) в конце

### Optional fields: body and description

`Тело` может содержать любую информацию о том на что ссылается данный коммит или же использоваться для более подробного описания проделанной работы.

- Является **необязательной** частью формата, **за исключением коммитов** типа `build(release)`, в таких типов коммитов должна прописывать сводная информация об изменениях проделанных в текущем релизе. *(Правила для подобного рода коммитов будут более конкретно описаны в “Release policy” ниже)*
- Может ссылаться на другие задачи, если какое-либо действие в этом коммите на них повлияло.

`Описание` может содержать информацию о модуле, в котором были проведены изменения.

- Является **необязательной** частью формата
