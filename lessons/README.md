# Уроки

Порядок прохождения и локальная нумерация находятся в [плане курса](../docs/course-plan.md). Здесь — навигация по существующим материалам. Папки разделов пронумерованы от `00` до `08` в порядке курса. Папки уроков имеют постоянные названия без номеров; название урока в документе также не содержит номера.

Для разработки используем [шаблон паспорта](lesson-template.md) и [требования](../docs/requirements.md). Материалы разделяются по читателю; внутри ученического и преподавательского документов размещаются блоки CAD. Существующие сценарные черновики переходят на этот формат постепенно. Готовность каждого урока и варианта CAD указывается только в его паспорте.

```text
lessons/
  00-section-name/
    lesson-name/
      lesson.md       паспорт, материалы и проверки по CAD
      student.md      общие задания и блоки действий по CAD
      teacher.md      общий замысел и блоки проведения по CAD
      drawings/       чертежи
      images/         иллюстрации и исходники
      models/         старт, запасной старт и эталон; варианты в nx/, fusion/ и т. п.
      handout/        памятка A5 и её редактируемые исходники
```

Каталоги материалов создаём по мере появления файлов. Для разделов без уроков оставлена короткая навигационная страница. Сохранившиеся персональные формулировки отражают исходный контекст разработки и не ограничивают аудиторию.

## Прежде чем начать

- [Виды и вращение модели](00-getting-started/views/lesson.md)
- [Видимость и сечения](00-getting-started/visibility-and-sections/lesson.md)
- [Измерение размеров и зазоров](00-getting-started/measure-distance/lesson.md)

## Эскизы: форма и размеры

- [Обрезка готовой геометрии; продление — дополнительно](01-sketches/trim/lesson.md)
- [Размеры и равенство](01-sketches/dimensions/lesson.md)
- [Геометрические связи](01-sketches/constraints/lesson.md)
- [Определённость эскиза](01-sketches/degrees-of-freedom/lesson.md)
- [Строительная геометрия, оси и симметрия](01-sketches/construction-geometry/lesson.md)

## От эскиза к объёмной детали

- [Выбор контуров — Selection Intent](02-solid-modeling/selection-intent/lesson.md)
- [Выдавливание: границы, направления, симметрия](02-solid-modeling/extrude/lesson.md)
- [Выдавливание до другой геометрии](02-solid-modeling/extrude-to-geometry/lesson.md)
- [Уклон стенок — Draft](02-solid-modeling/draft/lesson.md)
- [Вращение профиля — Revolve](02-solid-modeling/revolve/lesson.md)
- [Булевы операции и обрезка тела](02-solid-modeling/boolean-operations/lesson.md)
- [Построение по траектории — Sweep](02-solid-modeling/sweep/lesson.md)
- [Построение по сечениям — Through Curves](02-solid-modeling/through-curves/lesson.md)

## Как устроена модель и как её менять

- [Размещение эскиза: плоскость, оси, начало](03-model-structure/sketch-placement/lesson.md)
- [Опорные плоскости: смещение и угол](03-model-structure/datum-plane/lesson.md)
- [Касательные и срединные плоскости](03-model-structure/reference-planes/lesson.md)
- [История модели](03-model-structure/model-history/lesson.md)
- [Массивы и отражение — Pattern, Mirror](03-model-structure/pattern-and-mirror/lesson.md)

## Корпуса, стенки и рёбра

[Корпуса, стенки и рёбра](04-housings/README.md) — раздел для разработки; материалы уроков пока отсутствуют.

## Сборки и движение

- [Детали и компоненты сборки](05-assemblies/components/lesson.md)
- [Сборочные ограничения](05-assemblies/constraints/lesson.md)
- [Степени свободы и движение компонентов](05-assemblies/motion/lesson.md)

## Моделирование поверхностями

[Моделирование поверхностями](06-surfaces/README.md) — раздел для разработки; материалы уроков пока отсутствуют.

## Свободная форма

[Свободная форма](07-freeform/README.md) — раздел для разработки; материалы уроков пока отсутствуют.

## Самостоятельный проект

[Самостоятельный проект](08-projects/README.md) — раздел для разработки; материалы уроков пока отсутствуют.
