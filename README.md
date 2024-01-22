# Design Patterns On Python

Репозиторий содержит реализации паттернов проектирования на Python 3.

Паттерны проектирования — модель решения общих (часто встречающихся) проблем дизайна. Она (модель) описывает проблемы и основные подходы к их решению.

Паттерны делают нашу работу:

- последовательной
- понятной
- надежной

## Содержимое

Паттерны разбиты на категории по цели их использования.

### Порождающие паттерны

Эти паттерны отвечают за удобное и безопасное создание новых объектов или даже целых семейств объектов:

- [Фабрика (factory)](creational/factory.ipynb) — Используется для создания конкретных реализаций общего интерфейса.
- [Абстрактная фабрика (abstract factory)](creational/abstract_factory.ipynb) — Позволяет создавать семейства связанных объектов, не привязываясь к конкретике.
- [Строитель (builder)](creational/builder.ipynb) — Позволяет создавать сложные объекты пошагово.
- [Прототип (prototype)](creational/prototype.ipynb) — Позволяет копировать объекты, не вдаваясь в подробности их реализации.
- [Одиночка (singleton)](creational/singleton.ipynb) — Гарантирует, что у класса есть только один экземпляр, и предоставляет к нему глобальную точку доступа.

### Структурные паттерны

Эти паттерны отвечают за построение удобных в поддержке иерархий классов:

- [Адаптер (adapter)](structural/adapter.ipynb) — Позволяет объектам с несовместимым интерфейсом работать вместе.
- [Мост (bridge)](structural/bridge.ipynb) — Разделяет один или несколько классов на две отдельные иерархии — абстракцию и реализацию.
- [Компоновщик (composite)](structural/composite.ipynb) — Позволяет сгруппировать множество объектов в древовидную структуру и работать с ней.
- [Декоратор (decorator)](structural/decorator.ipynb) — Позволяет динамически добавлять объектам новую функциональность.
- [Заместитель (proxy)](structural/proxy.ipynb) — Позволяет подставлять вместо реальных объектов специальные объекты-заменители.
- [Легковес (flyweight)](structural/flyweight.ipynb) — Экономит память, разделяя общее состояние объектов между собой.
- [Фасад (facade)](structural/facade.ipynb) — Предоставляет простой интерфейс к сложной системе, классу или фреймворку.

### Поведенческие паттерны

Эти паттерны решают задачи эффективного и безопасного взаимодействия между объектами программы.:

- [Цепочка обязанностей (chain of responsibility)](behavioral/chain_of_responsibility.ipynb) — Позволяет передавать запросы последовательно по цепочке обработчиков.
- [Итератор (iterator)](behavioral/iterator.ipynb) — Дает возможность последовательно обходить элементы составных объектов, не раскрывая внутреннего представления.
- [Посредник (mediator)](behavioral/mediator.ipynb) — Позволяет уменьшить связанность множества объектов между собой.
- [Снимок (memento)](behavioral/memento.ipynb) — Позволяет сохранять текущее и восстанавливать прошлые состояния объектов.
- [Наблюдатель (observer)](behavioral/observer.ipynb) — Позволяет одним объектам следить и реагировать на изменения других объектов.
- [Состояние (state)](behavioral/state.ipynb) — Позволяет объектам менять поведение в зависимости от своего состояния.
- [Стратегия (strategy)](behavioral/strategy.ipynb) — Определяет семейство схожих объектов и помещает каждый из них в собственный класс.
- [Шаблонный метод (template method)](behavioral/template_method.ipynb) — Позволяет подклассам переопределять шаги алгоритма, не меняя общей структуры.
- [Посетитель (visitor)](behavioral/visitor.ipynb) — Позволяет добавлять в программу новые операции,не изменяя классы объектов, над которыми эти операции могут выполняться.
- [Команда (command)](behavioral/command.ipynb) — Превращает запросы в объекты, которые заключают в себе само действие и его параметры.