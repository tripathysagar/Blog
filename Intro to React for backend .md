# Intro to React for backend 

Aside from providing information to the user, a job of the web page is to handle the users input and reloading the webpage when required. The web framework react tries to solve those problem.
<br><br>
By using re-usable component. Which is basic building block. Where you have to write once and use the same component many times. React uses **JSX** (HTML like object with javascript). The react then translte that into HTML and JS during rendering. Consider following example of the brief overview.

### Basic print

```
    let x = 4;
    <p>value of x is : {x} </p>
```
which will translated to during rendering.
```
    <p>value of x is : 4</p>
```
Note: the object inside the "{}" must be atomic(i.e. string or number), list and object printing willl throw error

### If-Else Stament

```
    let x = 9;
    if(x > 10){
        return <p> x is grater than 10 </p>
    }else {
        return <p> x is less than 10 </p>
    }
```
During rendering it will be translated to 
```
    <p> x is less than 10 <p>
```


### For loop Stament

```
    let pos = {'x': 10, 'y':0}
    pos.map((index) => {
        return <div> {index} : {pos[index]} </div>
    })
```
During rendering it will be translated to 
```
    <div> x : 10 </div>
    <div> y : 0 </div>

```
