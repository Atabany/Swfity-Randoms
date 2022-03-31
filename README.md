# Swfity-Randoms

## I will share random thoughts about swift here 


------------------------------------------------------------------
### Key-path expressions as functions

Swift 5.2 introduced a shortcut which enables us to easily access the properties of objects

```

struct Person {
    let name : String
}
let mohamed = Person(name: "Mohamed")
let atabany = Person(name: "Atabany")

let people = [mohamed, atabany]
let names = people.map(\.name)
print(names)


```

------------------------------------------------------------------
