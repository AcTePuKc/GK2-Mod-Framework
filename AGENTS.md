# GK2 Mod Framework — локальные правила публикации

Перед любой разработкой, тестовой сборкой, релизом или cleanup обязательно следуй `D:\Modding\Workflows\MOD_LIFECYCLE.md`. Этот файл содержит только долговечные project-specific правила; текущая версия и publication state берутся из `STATUS.md` и `Publishing/PUBLISH_STATUS.md`.

Публикационные материалы этого проекта хранятся в `Publishing/`. Перед подготовкой или обновлением страницы, файла релиза либо анонса прочитай `Publishing/README.md` и `Publishing/PUBLISH_STATUS.md`, затем применяй общие правила из `D:/Modding/AGENTS.md` и соответствующие шаблоны `D:/Modding/Nexus/`, `D:/Modding/Discord/` или `D:/Modding/Boosty/`.

Не создавай публикационные `.bbcode` и тексты анонсов в корне проекта. `README.md` и `CHANGELOG.md` в корне — документы продукта и источники сведений для релиза; `STATUS.md` и `RELEASE_READINESS.md` — внутренние сведения о проверках.

`Publishing/` исключён из Git и из пользовательского release archive. Не считай черновики в нём опубликованными: это подтверждается отдельно и фиксируется в `Publishing/PUBLISH_STATUS.md`.
