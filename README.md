# Rekt
Rekt is a lightweight and fast ~~dependency injector~~ service locator for Kotlin inspired by [Kodein](https://github.com/Kodein-Framework/Kodein-DI), [Koin](https://github.com/InsertKoinIO/koin), and [Injekt](https://github.com/kohesive/injekt).

## Usage
```kotlin
fun main(vararg args : String) { 
  // start Rekt and initialize modules!
  getRekt {
    erekt(myModule)
  }
} 
```
