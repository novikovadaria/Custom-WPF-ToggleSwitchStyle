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
