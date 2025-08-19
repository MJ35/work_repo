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