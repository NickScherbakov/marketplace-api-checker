# marketplace-api-checker

Расширение конфигурации 1C:Enterprise для контроля API маркетплейсов.

## Как скопировать структуру проекта с локального компьютера

### Метод 1: Клонирование через Git (рекомендуется)

Если у вас уже есть Git на компьютере, это самый простой способ:

1. Откройте командную строку (Terminal/Command Prompt)
2. Перейдите в папку, где вы хотите разместить проект:
   ```bash
   cd путь/к/вашей/папке
   ```

3. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/NickScherbakov/marketplace-api-checker.git
   ```

4. Перейдите в папку проекта:
   ```bash
   cd marketplace-api-checker
   ```

Готово! Теперь у вас есть полная копия проекта со всей структурой директорий.

### Метод 2: Скачивание ZIP-архива

Если у вас нет Git:

1. Откройте страницу проекта: https://github.com/NickScherbakov/marketplace-api-checker
2. Нажмите кнопку **Code** (зелёная кнопка)
3. Выберите **Download ZIP**
4. Распакуйте скачанный архив в нужную папку на вашем компьютере

### Метод 3: Ручное копирование структуры

Если вы хотите скопировать только структуру директорий без файлов:

Структура проекта:
```
marketplace-api-checker/
├── CommonForms
├── ConfigDumpInfo.xml
├── Configuration.xml
├── LICENSE
└── README.md
```

Создайте такую же структуру на вашем компьютере:

**Windows (PowerShell):**
```powershell
mkdir marketplace-api-checker
cd marketplace-api-checker
New-Item -ItemType File -Name "CommonForms"
New-Item -ItemType File -Name "ConfigDumpInfo.xml"
New-Item -ItemType File -Name "Configuration.xml"
New-Item -ItemType File -Name "LICENSE"
New-Item -ItemType File -Name "README.md"
```

**Linux/Mac (Terminal):**
```bash
mkdir marketplace-api-checker
cd marketplace-api-checker
touch CommonForms ConfigDumpInfo.xml Configuration.xml LICENSE README.md
```

### Работа с конфигурацией 1C:Enterprise

Этот проект представляет собой расширение конфигурации 1C:Enterprise. Основные файлы:

- **Configuration.xml** - основной файл конфигурации с метаданными
- **ConfigDumpInfo.xml** - информация о версиях компонентов конфигурации
- **CommonForms** - общие формы конфигурации

Для работы с этим проектом в 1C:Enterprise:

1. Откройте Конфигуратор 1C
2. Создайте новую информационную базу или откройте существующую
3. Загрузите конфигурацию из XML-файлов через меню "Конфигурация" → "Загрузить конфигурацию из файла"

## Дополнительная информация

- **Версия**: 0.0.1
- **Назначение**: Расширение для контроля API маркетплейсов (НОПик)
- **Сайт**: http://nopi.pro
- **Лицензия**: См. файл LICENSE

## Требования

- 1C:Enterprise платформа версии 8.3.16 или выше
- Режим совместимости: Version8_3_16

## Контакты

Если у вас возникли вопросы или проблемы, создайте Issue в этом репозитории.