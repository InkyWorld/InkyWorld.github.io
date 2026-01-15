# Russian to Ukrainian Translation - Clean Architecture Documentation

## Overview
This document describes the comprehensive translation of Clean Architecture technical documentation from Russian to Ukrainian.

## Translation Script
**File:** `final_translate.py`  
**Location:** `/home/runner/work/books.github.io/books.github.io/final_translate.py`

## Statistics
- **Total Translation Pairs:** 618+
- **Files Translated:** 45/45 HTML files
- **Source Directory:** `book_clean_architecture/ru/`
- **Output Directory:** `book_clean_architecture/ua/`

## Features

### 1. Massive Translation Dictionary (618+ pairs)
The script contains a comprehensive dictionary covering:
- Common Russian words and particles
- All major verbs in multiple forms
- Adjectives and their declensions
- Technical DDD terminology
- Architecture-specific terms
- Complete phrases and sentences

### 2. Smart Translation
- **Word Boundary Detection:** Avoids partial word matches using regex
- **Phrase Prioritization:** Translates multi-word phrases before single words
- **Context Awareness:** Handles prepositions, conjunctions, and particles correctly

### 3. Structure Preservation
- ✅ HTML tags and structure intact
- ✅ CSS styles unchanged
- ✅ URLs and links preserved
- ✅ Python code syntax NOT translated
- ✅ Python comments ARE translated
- ✅ Technical proper names preserved (SOLID, CQRS, Repository, etc.)

### 4. Language Attributes
- Changed `lang="ru"` to `lang="uk"`
- Updated language switcher: UA is now active (blue), RU points to `../ru/`

## Key Translations

### Navigation & Headers
- "Введение" → "Вступ"
- "Слои архитектуры" → "Шари архітектури"
- "SOLID принципы" → "SOLID принципи"
- "Тестирование" → "Тестування"
- "Инварианты" → "Інваріанти"
- "Мини-проекты" → "Міні-проєкти"
- "Послесловие" → "Післямова"

### Technical Terms
- "Бизнес-логика" → "Бізнес-логіка"
- "Зависимости" → "Залежності"
- "Репозиторий" → "Репозиторій"
- "Сущности" → "Сутності"
- "Агрегаты" → "Агрегати"
- "События" → "Події"

### Common Phrases
- "Зачем нам это нужно?" → "Навіщо нам це потрібно?"
- "Как писать код" → "Як писати код"
- "должен быть" → "повинен бути"
- "можно использовать" → "можна використовувати"

## Usage

```bash
python3 final_translate.py
```

The script will:
1. Read all HTML files from `book_clean_architecture/ru/`
2. Apply 618+ translation rules
3. Preserve code, structure, and formatting
4. Output translated files to `book_clean_architecture/ua/`

## Translation Coverage

### Common Words (100+)
в, на, от, для, как, что, это, не, с, также, может, должен, все, через, при, без, после, между, когда, если, где, чем, кто, etc.

### Verbs (80+)
создать, сохранить, использовать, изменить, передавать, возвращать, проверить, писать, работать, делать, читать, получать, отправить, добавить, требовать, позволять, знать, иметь, жить, зависеть, etc.

### Adjectives (60+)
новый, старый, важный, простой, сложный, разный, единый, отдельный, внешний, внутренний, etc.

### Nouns (120+)
проект, система, данные, событие, логика, правило, объект, модель, класс, метод, функция, интерфейс, приложение, задача, результат, состояние, поле, таблица, транзакция, ошибка, операция, запрос, сообщение, код, слой, база, пользователь, заказ, товар, тест, реализация, сервис, etc.

### DDD & Architecture Terms (80+)
Domain Layer, Application Layer, Infrastructure Layer, Presentation Layer, Bounded Context, Ubiquitous Language, Aggregates, Entities, Value Objects, Repository, Unit of Work, Domain Events, Policies, Specification, Anti-Corruption Layer, etc.

## Quality Assurance

### Code Preservation
- Python syntax remains intact
- Only comments within code blocks are translated
- HTML/CSS/JavaScript code untouched

### Example (Before/After)
**Before (Russian):**
```python
# Бизнес-логика (Domain)
# Импортируем БД напрямую
from sqlalchemy.orm import Session
```

**After (Ukrainian):**
```python
# Бізнес-логіка (Domain)
# Імпортуємо БД напряму
from sqlalchemy.orm import Session
```

## Files Translated (45 total)
- acl.html
- advanced_techniques.html
- afterword.html
- aggregates.html
- antipatterns.html
- application.html
- background_tasks.html
- big_ball_of_mud.html
- boundaries_first.html
- bounded_context.html
- concurrency.html
- config_logging.html
- context_map.html
- context_relationships.html
- cqrs_es.html
- dependency.html
- deployment.html
- domain.html
- domain_events.html
- error_handling.html
- event_storming.html
- frameworks_django.html
- index.html
- infrastructure.html
- invariants.html
- middleware.html
- modular_monolith.html
- observability.html
- outbox.html
- overengineering.html
- policies.html
- presentation.html
- project_structure.html
- projects.html
- repository_uow.html
- saga.html
- security.html
- solid.html
- specification.html
- strategic_distillation.html
- strategic_integration.html
- subdomains.html
- testing.html
- ubiquitous_language.html
- versioning.html

## Author
Translation script created for Clean Architecture Guide by Alex | InkyWorld
