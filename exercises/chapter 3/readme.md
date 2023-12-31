# УПРАЖНЕНИЯ ГЛАВЫ 3
Попробуйте написать несколько коротких программ, чтобы получить предварительное представление о списках Python. Возможно, для упражнений из каждой главы стоит создать отдельную папку, чтобы избежать путаницы.
* 3-1. Имена: сохраните имена нескольких своих друзей в списке с именем names. Выведите имя каждого друга, обратившись к каждому элементу списка (по одному за раз).
* 3-2. Сообщения: начните со списка, использованного в упражнении 3-1, но вместо вывода имени каждого человека выведите сообщение. Основной текст всех сообщений должен быть одинаковым, но каждое сообщение должно включать имя адресата.
* 3-3. Собственный список: выберите свой любимый вид транспорта (например, мотоциклы или машины) и создайте список с примерами. Используйте свой список для вывода утверждений об элементах типа: «Я хотел бы купить мотоцикл Honda».

Следующие упражнения немного сложнее упражнений из главы 2, но они предоставляют возможность попрактиковаться в выполнении всех описанных операций со списками.
* 3-4. Список гостей: если бы вы могли пригласить кого угодно (из живых или умерших) на обед, то кого бы вы пригласили? Создайте список, включающий минимум трех людей, которых вам хотелось бы пригласить на обед. Затем используйте этот список для вывода пригласительного сообщения каждому участнику.
* 3-5. Изменение списка гостей: вы только что узнали, что один из гостей прийти не сможет, поэтому вам придется разослать новые приглашения. Отсутствующего гостя нужно заменить кем-то другим. 
  * Начните с программы из упражнения 3-4. Добавьте в конец программы команду print для вывода имени гостя, который прийти не сможет.
  * Измените список и замените имя гостя, который прийти не сможет, именем нового приглашенного.
  * Выведите новый набор сообщений с приглашениями – по одному для каждого участника, входящего в список.
* 3-6. Больше гостей: вы решили купить обеденный стол большего размера. Дополнительные места позволяют пригласить на обед еще трех гостей.
  * Начните с программы из упражнения 3-4 или 3-5. Добавьте в конец программы команду print, которая выводит сообщение о расширении списка гостей.
  * Добавьте вызов insert() для добавления одного гостя в начало списка.
  * Добавьте вызов insert() для добавления одного гостя в середину списка.
  * Добавьте вызов append() для добавления одного гостя в конец списка.
  * Выведите новый набор сообщений с приглашениями – по одному для каждого участника, входящего в список.
* 3-7. Сокращение списка гостей: только что выяснилось, что новый обеденный стол привезти вовремя не успеют, и места хватит только для двух гостей.
  * Начните с программы из упражнения 3-6. Добавьте команду для вывода сообщения о том, что на обед приглашаются всего два гостя.
  * Используйте метод pop() для последовательного удаления гостей из списка до тех пор, пока в списке не останутся только два человека. Каждый раз, когда из списка удаляется очередное имя, выведите для этого человека сообщение о том, что вы сожалеете об отмене приглашения.
  * Выведите сообщение для каждого из двух человек, остающихся в списке. Сообщение должно подтверждать, что более раннее приглашение остается в силе.
  * Используйте команду del для удаления двух последних имен, чтобы список остался пустым. Выведите список, чтобы убедиться в том, что в конце работы программы список действительно не содержит ни одного элемента.