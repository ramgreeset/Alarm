<h3>С чем работал</h3>


<ol>
<li>представление Button</li>
<li>setAlarm = findViewById(R.id.alarm_button) поиск представления по id</li>
<li>setAlarm.setOnClickListener слушатель элемента по клику</li>


</ol>


<h3>Ошибки</h3>

<ol>
<li>Простая ошибка синтаксиса. При работе с MaterialTimePicker.Builder были добавлены лишние скобки.</li>
<li>Ошибка связанная со старой версией API SDK в проекте. targetSdk меняется в папке Gradle Scripts -> build.gradle</li>
<li>Имя файла package com.example. должно совпадать с названием папки проекта</li>


</ol>
