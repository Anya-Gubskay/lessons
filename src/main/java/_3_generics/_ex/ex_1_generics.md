### Generics

1. Создать класс `Pair`, параметризованный двумя
параметрами `K` и `V`. Класс должен хранить две
переменные типов `K` и `V` соответственно. У
класса должен быть конструктор,
принимающий 2 параметра типов `K` и `V`, а
также набор соответствующих геттеров/сеттеров.

2. Создать статический обобщённый метод swap в final классе PairUtil.
 Метод должен принимать объект класса Pair и возвращать пару, в которой элементы поменяны местами.

3. Реализуйте следующий метод:\
   `@SafeVarargs public static final <T> T[] repeat(int n, T... objs)`\
   Он должен возвращать массив `n` копий заданных объектов.

4. ***Реализуйте обобщенный класс `Stack<E>`, используя массив для хранения элементов.
    Предоставьте методы `push()`, `рор()` и `isEmpty()`.