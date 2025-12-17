# DemoQA — Basic Smoke Checklist
Ссылка: https://demoqa.com  
Описание: Быстрая проверка ключевых страниц и базовых сценариев.

| ID  | Check item                                 | Expected result                                       | Severity | Notes / Repro steps                        | Status |
|-----|--------------------------------------------|-------------------------------------------------------|----------|--------------------------------------------|--------|
| S-01| Открытие сайта                              | Главная страница загружается, нет ошибок в консоли    | Major    | Открыть https://demoqa.com                 | [ ]    |
| S-02| Elements                                    | Страница Elements доступна и подменю видны            | Major    | Клик → Elements                             | [ ]    |
| S-03| Forms                                       | Practice Form открывается                             | Major    | Клик → Forms → Practice Form                | [ ]    |
| S-04| Alerts/Windows                              | Alerts/Frames/Windows доступны                        | Medium   | Клик → Alerts, проверить опции              | [ ]    |
| S-05| Widgets                                     | Widgets доступны и рабочие                            | Medium   | Клик → Widgets, взаимодействовать           | [ ]    |
| S-06| Interactions                                | Drag/Drop и др. работают                              | Medium   | Клик → Interactions, выполнить drag/drop    | [ ]    |
| S-07| Book Store App                              | Bookstore доступен, страницы книг/профиля открываются | Major    | Клик → Book Store                            | [ ]    |
| S-08| Адаптивность                                | Страницы читаемы на мобильных разрешениях             | Medium   | Проверить 320/375/768                       | [ ]    |
| S-09| Консоль                                      | Нет ошибок уровня error в DevTools                    | Major    | Открыть DevTools -> Console                 | [ ]    |
