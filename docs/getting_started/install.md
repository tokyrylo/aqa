# Установка Python и IDE
Python — это язык программирования, а IDE (среда разработки) — это программа, где удобно писать код (как «Word», только для программистов).

Мы установим:

1. **Python** — чтобы компьютер понимал код.

2. **VS Code** или **PyCharm** — чтобы удобно писать программы.

## 1. Проверка, есть ли Python

Перед установкой можно проверить, не установлен ли Python уже.

- **Windows**

   - Нажмите `Win + R`.

   - Введите `cmd` и нажмите `Enter`.

   - В открывшемся окне напишите:

```bash
python --vesion
```
или
```bash
py --version
```
   - Если появилось что-то вроде `Python 3.11.6`, значит, он уже есть.

- **macOS / Linux**

   - Откройте «Терминал».
   - Напишите: 

```bash
python3 --version
```
или
```bash
python --version
```
   - Если появилась версия - Python установлен.

## 2. Установка Python

**Windows**

1. Заходим на сайт: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Нажимаем жёлтую кнопку **Download Python 3.x.x**.
3. Запускаем скачанный файл.
4. Важно: поставьте галочку **“Add Python to PATH”** (это нужно, чтобы Python работал из командной строки).
5. Нажимаем **Install Now**.
6. После завершения снова проверяем:
```bash
python --version
```

**macOS**

1. На новых версиях macOS Python 3 может быть предустановлен. Проверяем:
```bash
python3 --version
```
**Linux (Ubuntu, Debian, Mint и др.)**

1. Откройте терминал.

2. Введите:

```bash
sudo apt update
sudo apt install python3
```

3. Проверяем:

```bash
python3 --version
```

## 3. Установка IDE

**VS Code (Visual Studio Code)**

1. Сайт: [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Скачайте версию под вашу ОС (Windows / macOS / Linux).
3. Установите как обычную программу.
4. После установки откройте VS Code.
5. Установите расширение Python (слева вкладка Extensions → ищем “Python” → Install).

**PyCharm (специализированная IDE для Python)**

1. Сайт: [https://www.jetbrains.com/pycharm/download/](https://www.jetbrains.com/pycharm/download/)
2. Скачайте версию Community (она бесплатная).
3. Установите и запустите.