##### Заполните таблицу.

Коллекция | Основная функциональность |  Примеры типичного использования 
----------|---------------------------|--------------------------------------------------
Set       | Set — множество неповторяющихся объектов. В коллекции этого типа разрешено наличие только одной ссылки типа null. | Множества с уникальными значениями, в которые можно добавлять и из которых можно удалять значения. К ним можно отнести приглашённых гостей, файлы с одинаковым расширением в одной папке, слова в словарном запасе и т.д.          
List      | List хранит объекты, которые могут повторяться, в порядке вставки. | Списки любых объектов. К ним можно отнести товары на складе, оценки студентов, имена сотрудников и т.д.         
Queue     | Queue — коллекция, предназначенная для хранения элементов в порядке, нужном для их обработки. В дополнение к базовым операциям интерфейса Collection, очередь предоставляет дополнительные операции вставки, получения и контроля. Очереди обычно, но не обязательно, упорядочивают элементы в FIFO порядке. | Используются, например, для создания очередей потоков, которые работают с одним объектом коллекции, или в качестве стека и т.д.
Map       | Map используется для отображения каждого элемента из одного множества объектов (ключей) на другое (значений). При этом, каждому элементу из множества ключей ставится в соответствие ровно 1 элемент из множества значений. В то же время одному элементу из множества значений может соответствовать 1, 2 и более элементов из множества ключей. Интерфейс java.util.Map\<K,V> описывает функциональность ассоциативных массивов. | Используются в качестве словарей, в парах ID пользователя = список кошельков, клавиша = выполняемое действие, номер паспорта = список стран, в которых побывал гражданин и т.д.                       |          