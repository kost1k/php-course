В качестве пакетного менеджера используется [pnpm](https://github.com/pnpm/pnpm).

Инструкцию по установке можно посмотреть на [npmjs](https://www.npmjs.com/package/pnpm).

Команда `pnpm dev` запускает режим разработки, в терминале будут выведены ссылки для редактирования и предварительного просмотра markdown файлов в графическом редакторе.

Команда `pnpm build` запускает production сборку для деплоя.

Добавлен `action`, кторый при пуше в мастер делает `build` и разворачивает его на `gh-pages`.