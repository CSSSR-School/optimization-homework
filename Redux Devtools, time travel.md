**Redux Devtools, time travel**

Одному из сотрудников веб-разработки пришла срочная задача - сделать в минимальном виде калькулятор на связке реакт-редакс. 
С заданием он справился, и даже заснял короткий видеоролик того, как его код работает. Но, к сожалению, часть его кода была потеряна.

Уцелевший кусок кода предлагается доработать до полноценного приложения, используя сохраненный лог работы стора из расширения хрома Redux Devtools.
Задание считается выполненным в случае, если при запуске воспроизведения экшнов из redux devtools калькулятор отработает так, как записано в прилагаемом видеоролике.

Изменять в приложении можно только пустые блоки, помеченные многоточиями:

```
const calcState = {
//...
} 

const calcReducer = (state = calcState, action) => {
//...
}

const mapStateToProps = (state) => {
//...
}

const mapDispatchToProps = (dispatch) => {
//...
}  
```

JSON-запись из Devtools находится в самом начале, записана в константу ReduxDevToolsPayload

[Сохранившийся кусок кода](https://codepen.io/Ilrilan/pen/Ydaejy)

[Видеозапись рабочего приложения](http://take.ms/6Zdy4)


