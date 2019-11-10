
Using the State Hook:

```
import React,{useState}from'react';

function example(){
 //declare a new state variable,which we'll call"count"
const[count,setcount]=useState(0);


Return(
 <div>
  <p>You clicked{count}times</p>
  <button onClick={() => setCount(count+1)}>
  Click me
  </button>
 </div>
);
}
```
