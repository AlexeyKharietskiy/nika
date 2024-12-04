# Агент распознавания речи

Данный агент распознает речь, сказанную пользователем.

**Класс действий:**

`action_recognize_audio`

**Параметры:**

1. `messageAddr` -- элемент класса `concept_message`.

### Пример

Пример входной структуры:

<img src="../images/audioRecognitionAgentInput.png"></img>

Пример выходной структуры:

<img src="../images/audioRecognitionAgentOutput.png"></img>

### Язык реализации агента
Python

### Результат

Возможные результаты:

* `SC_RESULT_OK` - агент создал структуру с распознанным текстом.
* `SC_RESULT_ERROR`- внутренняя ошибка.
