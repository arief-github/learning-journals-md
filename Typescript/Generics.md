
**Keywords**

1). a piece of code may be intended to **work with various different types** depending on how it’s
called.
2). we need a **way to say** that there is a relationship between **the input and the type the function returns**.
3). A function may be made generic by **placing an alias for a type parameter,** **wrapped in**
**angle brackets**, immediately before the parameters parentheses. 


**Snippet Code Examples**

```ts
function identity<T>(input: T) {
    return input
}

const numeric = identity(10)
const says = identity("Hello")
```

![[Pasted image 20240810075918.png]]
