# Switch Statements



```kotlin
val name = "Vitor"
    when (name) {
        "Vitor" -> println(name)
        "Laila" -> println("AuAu")
        else -> {
            println("Invalid String")
        }
    }

val num = 1
val result =  when(num) {
        is Int -> "is an Int"
        !is Double -> "is not Double"
        is String -> "is a String"
        else -> "is none of the above"
    }
```
