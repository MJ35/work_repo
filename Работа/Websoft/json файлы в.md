1.
Максим Юрков сделал вот так в некий момент:

Revision: 265a47015a85d5047622c9e036be31b7288dcc60
Author: maksimyurkov <yurkov.maksim.sergeevich@gmail.com>
Date: 04.04.2023 15:17:11
Message:
#20015 В файлах виден путь расположения папки у разработчика

----
Modified: WebSoftServer/wtv/libs/analytics_library.json
Modified: WebSoftServer/wtv/libs/app_tests_library.json
Modified: WebSoftServer/wtv/libs/course_player_library.json
Modified: WebSoftServer/wtv/libs/poll_player_library.json
Added: WebSoftSources/apps/analytics/build/change-lib-file.js
Modified: WebSoftSources/apps/analytics/package.json
Added: WebSoftSources/apps/courses/build/change-lib-file.js
Modified: WebSoftSources/apps/courses/package.json
Added: WebSoftSources/apps/polls/build/change-lib-file.js
Modified: WebSoftSources/apps/polls/package.json
Added: WebSoftSources/apps/tests/build/change-lib-file.js
Modified: WebSoftSources/apps/tests/package.json

Это было сделано не для всех имеющихся json файлов в каталоге WebSoftServer/wtv/libs/, а только для некоторых.


2.
Начиная с какого-то момента на стендах QA после разворачивания, json файлы генерируются (перегенерируются) автоматически.

Это видно (в частности) по значению тэга "path".

Пример:
E:\WebSoft\2025.2.1215\WebSoftServer\wtv\libs\talentpool_library.json
[
  {
    "id": "integer",
    "longname": "integer",
    "name": "integer",
    "kind": "typedef",
    "scope": "global",
    "type": {
      "names": [
        "module:classes_library~integer"
      ]
    },
    "meta": {
      "lineno": 6,
      "filename": "talentpool_library.js",
      "path": "C:\\gitea_runner\\build_dir\\ca74b8f2d05ad9c0\\hostexecutor\\WebSoftServer\\wtv\\libs"
    },
    "order": 1
  },
  {
    "id": "int",
    "longname": "int",
    "name": "int",
    "kind": "typedef",
    ...