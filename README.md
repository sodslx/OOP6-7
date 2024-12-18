# 🗂️ Quoted-Printable Encoding and Decoding Project

## 📋 Описание проекта
Этот проект реализует **алгоритма кодирования/декодирования Quoted-Printable** на языке **C++**.  
Программа автоматически читает текстовые файлы, кодирует или декодирует их и сохраняет результаты в новые файлы.

## 🔎 Что такое Quoted-Printable?
Quoted-Printable – механизм конвертации, относящийсякспецификации MIME (Multipurpose Internet Mail Extensions). Текущаяспецификация MIME описана в RFC 1521.
Данный механизм конвертации применим только ктекстовымдокументам.
Для конвертации исполняемых файлов, графическихивидеофайлов лучше использовать механизм конвертации BASE64.
Quoted-Printable предполагает конвертацию всех символоввсимволыиспользующиеся в наборе символов ASCII.

## 🚀 Возможности
1. **Кодирование файлов** — преобразование текстовых данных в формат Quoted-Printable.
2. **Декодирование файлов** — восстановление исходного текста из формата Quoted-Printable.
3. **Автоматическая обработка файлов**:
   - Исходные файлы Для кодирования: encode.cpp
   - Исходные файлы для декодирования: decode.cpp
---
## 📂 Структура проекта

```plaintext
Quoted-Printable-lab-work/
│
├── main.cpp               # Исходный код программы
└── README.md              # Описание проекта
```
---
## 🚀 Как запустить код
1. **Компиляция программы**  
   Скомпилируйте файл `main.cpp` с помощью компилятора g++:
   ```bash
   g++ main.cpp -o Quoted-Printable_project
2. **Запуск программы**
   Запустите скомпилированный файл:
   ./Quoted-Printable_project 
---
# Что делает программа
1.Берет исходную строку, содержащую текст на русском языке.
2.Кодирует ее в формат Quoted-Printable, заменяя специальные символы и символы Юникода на их кодированные версии.
3.Выводит закодированную строку в консоль.
4.Пытается декодировать закодированную строку обратно в исходную строку.
5.Выводит декодированную строку в консоль.
6.В случае ошибки декодирования, выводит сообщение об ошибке в поток ошибок.
## 🙌 Благодарности

- **Тимлид** — за качественную организацию работы.
- **Проджект-Менеджер** — за четкое планирование и документацию.
- **Программист** — за написание и отладку кода.
- **Преподаватель** — за предоставленное задание и поддержку.
