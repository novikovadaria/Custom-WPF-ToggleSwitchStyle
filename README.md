# WPF ToggleSwitch Style

Этот репозиторий содержит кастомный стиль для элемента управления `CheckBox` в WPF, который имитирует поведение `ToggleSwitch` (переключатель).

## Предпросмотр

![image](https://github.com/novikovadaria/Custom-WPF-ToggleSwitchStyle/assets/107907983/76909235-e764-4a9d-b5ac-cd23c9fcd159)
![image](https://github.com/novikovadaria/Custom-WPF-ToggleSwitchStyle/assets/107907983/97ea8cce-bdcd-4064-9ef2-3862e831a080)

## Установка

1. Склонируйте репозиторий или скачайте содержимое файла со стилем.
2. Добавьте стиль в ваш проект WPF (например, в файл `App.xaml` или в другой ресурсный файл).

## Использование

Для того чтобы применить стиль к `CheckBox`, укажите имя стиля в свойстве `Style` вашего элемента:

```xml
<CheckBox Style="{StaticResource ToggleSwitchStyle}" />
```

## Идея

Иногда стандартные решения не могут удовлетворить все наши потребности. Когда я столкнулась с необходимостью отображения активности товара на сайте, использование обычного CheckBox показалось мне не совсем подходящим вариантом. Я искала более интуитивно понятное и визуально приятное решение — и мне захотелось использовать ToggleSwitch.

Но, как оказалось, для WPF нет встроенного элемента ToggleSwitch. Я попробовала использовать сторонние библиотеки, однако столкнулась с различными проблемами, начиная от конфликтов в пространстве имен и заканчивая другими неудобствами.

В конечном итоге, это подтолкнуло меня к решению создать свой собственный ToggleSwitch, который бы сочетал в себе функциональность и простоту использования. И вот он перед вами!

# WPF ToggleSwitch Style

This repository supports the standard mode for installing `CheckBox` in WPF, which simulates the inclusion of `ToggleSwitch' (switch).

## Preview

![image](https://github.com/novikovadaria/Custom-WPF-ToggleSwitchStyle/assets/107907983/76909235-e764-4a9d-b5ac-cd23c9fcd159)
![image](https://github.com/novikovadaria/Custom-WPF-ToggleSwitchStyle/assets/107907983/97ea8cce-bdcd-4064-9ef2-3862e831a080)

## Installation

1. Clone the repository or download the contents of the file with the style.
2. Add text to your WPF project (for example, downloaded the App.xaml or to another custom file).

## Usage

In order to add a style to the "Checkbox", specify it in the "Style" of your application:

```xml
<CheckBox Style="{StaticResource ToggleSwitchStyle}" />
```

## Idea

Sometimes standard solutions cannot meet all our needs. When I was faced with the inability to display product information on the site, using an additional checkbox seemed to me not quite the right option. I was looking for a more intuitive and visually appealing change — and I wanted to use the toggle switch.

No, as it turned out, there is no built-in switch for WPF. I tried using third-party libraries, but I ran into various problems, ranging from namespace conflicts to other inconveniences.

In the end, this prompted me to re-install my own toggle switch, which I would consider in its functionality and ease of use. And here it is!
