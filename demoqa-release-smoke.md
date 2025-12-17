# DemoQA — Release / Smoke Checklist
Ссылка: https://demoqa.com  
Описание: Быстрые критичные проверки перед публичным прогоном.

| ID   | Check item                                  | Expected result                                            | Severity | Notes / Repro steps                         | Status |
|------|---------------------------------------------|------------------------------------------------------------|----------|---------------------------------------------|--------|
| R-01 | Основные страницы                           | Elements/Forms/Alerts/Widgets/Interactions/Bookstore OK     | Blocker  | Прогон основных страниц                     | [ ]    |
| R-02 | Practice Form submit                         | Успешная отправка формы (modal)                             | Blocker  | Заполнить и Submit                          | [ ]    |
| R-03 | Web Tables CRUD                              | Добавление/редактирование/удаление работают                 | Blocker  | Add/Edit/Delete в Web Tables                | [ ]    |
| R-04 | Bookstore add/remove                         | Добавление книги в коллекцию + удаление                     | Blocker  | Add book → Profile → Remove                 | [ ]    |
| R-05 | Alerts/Windows behaviour                      | Alerts/Confirm/Prompt работают                              | Major    | Проверить все типы alert                    | [ ]    |
| R-06 | Интеграции/скрипты                            | Нет JS ошибок при критических сценариях                     | Major    | Проверить Console при действиях             | [ ]    |
| R-07 | Performance quick check                       | Ключевые страницы открываются < 3–4s                        | Major    | Открыть страницы и замерить время загрузки  | [ ]    |
