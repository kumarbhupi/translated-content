---
title: <angle>
slug: Web/CSS/angle
---

{{ CSSRef() }}

[Тип данных](/ru/docs/Web/CSS/CSS_Types) [CSS](/ru/docs/Web/CSS) **`<angle>`** представляет собой значение угла, выраженное в градусах, градах, радианах или оборотах. Он используется, например, в {{cssxref ("&lt;gradient&gt;")}} и в некоторых функциях {{cssxref ("transform")}}.

{{EmbedInteractiveExample("pages/css/type-angle.html")}}

## Синтаксис

Тип данных `<angle>` состоит из числа ({{cssxref("&lt;number&gt;")}}), за которым следует одна из единиц измерения, представленные ниже. Между литералом единицы измерения и цифрой нет пробела. После `0` указывать единицу измерения необязательно.

Опционально перед числом может стоять знак `+` или `-` . Положительное значение отмеряется по часовой стрелке, а отрицательные – против часовой. Чтобы достичь статистических свойств, каждый угол может быть представлен разными значениями, эквивалентными друг другу. Например, `90deg` равняется `-270deg`, а `1turn` равняется `4turn`. Тем не менее, для достижения динамических свойств эффект будет другим. Например, при применении {{cssxref ("animation")}} или {{cssxref ("transition")}}.

### Единицы измерения

- deg
  - : Представляет угол в [градусах](<https://ru.wikipedia.org/wiki/Градус_(геометрия)>). Один полный круг равен `360deg`. Например: `0deg`, `90deg`, `14.23deg`.
- grad
  - : Представляет угол в [градах](https://ru.wikipedia.org/wiki/Град,_минута,_секунда). Один полный круг равен `400grad`. Например: `0grad`, `100grad`, `38.8grad`.
- rad
  - : Представляет угол в [радианах](https://ru.wikipedia.org/wiki/Радиан). Один полный круг равен 2π или примерно `6.2832rad`. `1rad` - это 180/π градусов. Например: `0rad`, `1.0708rad`, `6.2832rad`.
- turn
  - : Представляет угол в количестве [оборотов](<https://ru.wikipedia.org/wiki/Оборот_(единица_измерения)>). Один полный круг равен `1turn`. Например: `0turn`, `0.25turn`, `1.2turn`.

## Примеры

| ![Angle90.png](/@api/deki/files/5704/=Angle90.png)           | Прямой угол: `90deg = 100grad = 0.25turn ≈ 1.5708rad`                              |
| ------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| ![Angle180.png](/@api/deki/files/5706/=Angle180.png)         | Развёрнутый угол: `180deg = 200grad = 0.5turn ≈ 3.1416rad`                         |
| ![AngleMinus90.png](/@api/deki/files/5707/=AngleMinus90.png) | Прямой угол (против часовой стрелки): `-90deg = -100grad = -0.25turn ≈ -1.5708rad` |
| ![Angle0.png](/@api/deki/files/5708/=Angle0.png)             | Нулевой угол: `0deg = 0grad = 0turn = 0rad`                                        |

## Спецификации

{{Specifications}}

## Совместимость с браузерами

{{Compat}}
