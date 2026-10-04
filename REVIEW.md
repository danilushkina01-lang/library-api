# REVIEW.md — Чек-лист самопроверки

- [ ] **REST-ресурсы**: CRUD для Books и Readers; Loans: создание, список, получение по ID, возврат.
- [ ] **Схемы**: Описаны схемы Book, Reader, Loan, ErrorResponse.
- [ ] **Ошибки**: Единый формат ErrorResponse со всеми кодами из требований.
- [ ] **Идемпотентность**: POST /loans требует Idempotency-Key.
- [ ] **Бизнес-правила**: В описании операций учтены правила выдачи, возврата, дат и удаления.
- [ ] **Документация**: Теги Books/Readers/Loans; summary/description для ключевых операций; минимум 3 примера.
- [ ] **STYLE.md**: 5–10 правил API.
- [ ] **README.md**: Краткое описание проекта.
- [x] **Deprecated поле**: В схеме Book поле `published_year` помечено как `deprecated: true`.
