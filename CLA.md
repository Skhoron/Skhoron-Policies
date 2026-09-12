# Developer Certificate of Origin (DCO)

Применяется ко всем проектам Skhoron, которые прямо ссылаются на эту политику.

> Файл исторически называется `CLA.md`, но Skhoron использует **DCO, а не CLA**. Отдельное соглашение CLA этим документом не вводится.

## Developer Certificate of Origin 1.1

By making a contribution to this project, you certify that:

1. The contribution was created in whole or in part by you and you have the right to submit it under the open source license indicated in the project repository; or
2. The contribution is based upon previous work that, to the best of your knowledge, is covered by an appropriate open source license and you have the right under that license to submit that work, with or without modifications, under the same open source license; or
3. The contribution was provided directly to you by another person who certified (1), (2), or (3), and you have not modified it; and
4. You understand and agree that this project and the contribution are public and that a record of the contribution, including the identity information contained in the commit, may be maintained and distributed as part of the project.

## Как подтвердить

Каждый коммит, который вносится в проект, должен содержать строку `Signed-off-by`.

Используйте:

```bash
git commit -s -m "Описание изменения"
```

Это добавляет в сообщение коммита строку вида:

```text
Signed-off-by: Ваше Имя <email@example.com>
```

Подписывать отдельный документ не требуется.

Если конкретный репозиторий Skhoron использует DCO enforcement, коммиты без корректного sign-off не могут быть приняты до исправления.

## Важно о лицензии

DCO не выбирает лицензию проекта. В тексте выше намеренно используется формулировка «лицензия, указанная в репозитории проекта», потому что разные проекты Skhoron могут иметь разные лицензии.