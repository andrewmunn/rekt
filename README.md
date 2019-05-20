# Rekt
Rekt is a simple dependency ~~injector~~ locator for Kotlin inspired by [Kodein](https://github.com/Kodein-Framework/Kodein-DI), [Koin](https://github.com/InsertKoinIO/koin), and [Injekt](https://github.com/kohesive/injekt).

## Usage
```kotlin
fun main(vararg args : String) { 
  // start Rekt!
  getRekt {
    // erekt modules
    erekt(myModule)
  }
} 
```
