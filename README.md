[![RTAkland's GitHub stats](https://rdstat.vercel.app/api?username=RTAkland&theme=tokyonight)](https://github.com/RTAkland)
[![RTAkland's Top Language](https://github-readme-stats.vercel.app/api/top-langs/?username=RTAkland&layout=compact&theme=tokyonight)](https://github.com/RTAkland)

```kotlin
// About me

enum class Genders {
    Male, Female
}

fun main() {
    val name = "RTAkland"
    val gender = Genders.Male
    val org = "DangoTown"
    val languages = listOf("Kotlin", "Python")
    println("My Name is $name, and my gender is $gender, I am in ${org} (https://dgtmc.top).")
    languages.forEach {
        println("I use ${it}.")
    }
}
```
