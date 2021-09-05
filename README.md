# iu7_tester
Простой тестовый скрипт написанный на python для IU7-C с поддержкой аргументов.

## Скриншотики

Все ок:

![image](https://user-images.githubusercontent.com/42784580/132129446-83b60602-2d01-4044-bd09-37ed33e602e1.png)

Ошиб очка:

![image](https://user-images.githubusercontent.com/42784580/132129497-cf3bafe5-3411-4c7d-b790-a88c4c9dc87f.png)

## Dependencies
```
pip install rich
```

## Using
```
test.py ./path/to/lab_06_06_01
```

Папка должна иметь папку func_tests, вида как объясняли.
Пример:
```
$ tree .
.
├── movies.txt
├── neg_01_args.txt
├── neg_01_in.txt
├── neg_01_out.txt
├── neg_02_args.txt
├── neg_02_in.txt
├── neg_02_out.txt
├── pos_01_args.txt
├── pos_01_in.txt
├── pos_01_out.txt
├── pos_02_args.txt
├── pos_02_in.txt
├── pos_02_out.txt
└── readme.md
```

Где `_in.txt`  - вход, `_args.txt` - аргументы, `_out.txt` - выход.

## _args.txt

Агрументы перечисляются в 1 строчке. Пример:
```
./path/to/some/file arg1 --flag -option value
```
