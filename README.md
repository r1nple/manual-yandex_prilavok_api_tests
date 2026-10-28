# <a name="up" />Проект 5-го спринта по ручному тестированию - тестирование API приложения Яндекс.Прилавок
Разработчики сделали новую функциональность в API Яндекс.Прилавка.

## Содержание
- [Задачи тестировщика](#задачи-тестировщика)
- [Стэк](#стэк)
- [Процесс выполнения задач](#процесс-выполнения-задач)

## Задачи тестировщика

<details>
  <summary>Задачи проекта 5-го спринта</summary>

  
  **Предусловия**

**Тестовый стенд:** https://{id}.serverhub.praktikum-services.ru/

**Документация API:** https://{id}.serverhub.praktikum-services.ru/docs/

Работа с наборами: возможность добавлять продукты в набор — ручка **POST /api/v1/kits/{id}/products**

Работа с курьерами: возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит. Ручка **POST /fast-delivery/v3.1.1/calculate-delivery.xml**

Работа с корзиной:

возможность получить список продуктов, которые добавили в корзину. Ручка **GET /api/v1/orders/id**

возможность добавлять продукты в корзину. Ручка **PUT /api/v1/orders/:id**

возможность удалять корзину. Ручка **DELETE/api/v1/orders/:id**
  
  #### Задачи
  1. Проанализируй требования к новой функциональности бэкенда Яндекс.Прилавка. Изучи документацию к API в Apidoc. Требования к бэкенду находятся <a href="https://code.s3.yandex.net/qa/files/backend_requirements.pdf" target="_blank">здесь</a>.
  2. Спроектируй тесты в виде чек-листа, чтобы покрыть функциональность, которую тебе передали на тестирование: она описана выше. Авторизацию проверять не нужно.
  3. Протестируй API через Postman и заведи баг-репорты в Google Таблицу, если это понадобится.
  4. Отчёт о тестировании. Оформить проделанную работу в виде отчёта.

</details>

## Стэк
<img title="Google Docs" alt="Google Docs" height="50" alt="google-docs-icon-logo" src="https://github.com/user-attachments/assets/fd301995-227f-486b-a4cb-7f89066e6173" /> <img title="DevTools" height="50" alt="DevTools" src="https://github.com/user-attachments/assets/688075f1-49d9-417e-af2d-6ac48df2af13" /> <img title="Postman" alt="Postman" height="50" alt="postman-icon-logo" src="https://github.com/user-attachments/assets/87a06e01-6def-4cc4-bb05-0f4c6588d25b" />

## Процесс выполнения задач

<details>
 <summary>Задачи</summary>

### Задача 1
**Проанализируй требования к новой функциональности бэкенда Яндекс.Прилавка. Изучи документацию к API в Apidoc. Требования к бэкенду находятся <a href="https://code.s3.yandex.net/qa/files/backend_requirements.pdf" target="_blank">здесь</a>.**

<a href="https://docs.google.com/spreadsheets/d/1goMtzU3h3EpGRMc_rozaHsJU6TWtaxtN9grK_ujbTzo/edit?gid=1304990855#gid=1304990855" target="_blank">КЭ и ГЗ</a>.

### Задача 2
**Спроектируй тесты в виде чек-листа, чтобы покрыть функциональность, которую тебе передали на тестирование: она описана выше. Авторизацию проверять не нужно.**

<a href="https://docs.google.com/spreadsheets/d/1-o_i6Rx5Tx2fYSs3GQmewbBawbmeIzGwPwQAHE7wC5M/edit?gid=2006427015#gid=2006427015" target="_blank">Чек-лист</a>.

### Задача 3
**Протестируй API через Postman и заведи баг-репорты в Google Таблицу, если это понадобится.**

<a href="https://docs.google.com/spreadsheets/d/1-o_i6Rx5Tx2fYSs3GQmewbBawbmeIzGwPwQAHE7wC5M/edit?gid=1735019751#gid=1735019751" target="_blank">Баг-репорты с скриншотами</a>.

### Задача 4
**Отчёт о тестировании. Оформить проделанную работу в виде отчёта.**

<img width="545" height="376" alt="1" src="https://github.com/user-attachments/assets/4f7c3ee0-4863-478d-bfd1-5689fb4ede9b" />

</details>
