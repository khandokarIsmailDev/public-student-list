# Big Problem found
the problem is: when i add any data, `added successfull` but after adding , data did not show in `Student List`. Only show data when reload the page, its not Next js nature,

# Solution
In this case i use `router.refresh()`.  
```js
import  {useRouter} from "next/navigation";

funciton MyComponent(){
    const router = useRouter()

    router.refresh()
}
```











#### [Know More](https://www.youtube.com/watch?v=MbUJdMXbaNc) show this video