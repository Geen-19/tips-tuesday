# tips-tuesday
### What is a Hook?
A hook is a special function that helps us to access usefull react features.
For Example useState is a hook that helps to add react state to funcion components.
### When are hooks useful?
If you have wrote some code in a function component and you realise that the you need to add some state to it, then you can use a hook inside the function component (previosuly it was achieved by changing it to a class). 
### What does caliing useState do?
It first declares our variable as a state variable. Normally variables disappear when the function exits but the state variables are preserved by React.
### What do we pass in useState argument?
The argument that we pass in useState is the initial state of the hook!
```
const [count, setCount] = useState(0);
```
In order to update the current count, we can call the setCount().
 ```
setCount(count + 1)
```
React will remember the current value between re-renders and provide the most recent one to our function. 

![snippet](/ss.png)

In this Example, we just want how many times the user clicked the "Click Me" Button, so the setCount(count + 1) is used whenever the the button is clicked, thereby react preserves state variables between re renders and update the count value!!!
