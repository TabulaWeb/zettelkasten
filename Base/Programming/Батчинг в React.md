#programmin #JS 

Батчинг в реакте, это изменение состояния нескольких стейтов в один этап рендеринга.

```JS
const [count, setCount] = useState(0); 
const [flag, setFlag] = useState(false); 
function handleClick() { 
	setCount(c => c + 1); // Не вызывает ререндер
	setFlag(f => !f); // Не вызывает ререндер 
	// React вызовет ререндер только один раз, в конце 
}
```
