# lecture_52_JS_Forms_controls_Focus_blur  

#  [Задачи ](https://github.com/schoolteacherMP/lecture_52_JS_Forms_controls_Focus_blur/blob/main/tasks.md)  

События `focus` и `blur` срабатывают на фокусировке/потере фокуса элемента.  

Их особенности:  

- Они не всплывают. Но можно использовать фазу перехвата или `focusin/focusout`.  
- Большинство элементов не поддерживают фокусировку по умолчанию. Используйте `tabindex`, чтобы сделать фокусируемым любой элемент.  

Текущий элемент с фокусом можно получить из `document.activeElement`.  


