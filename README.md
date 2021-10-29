[![1552980358's github stats](https://github-readme-stats.vercel.app/api?username=1552980358&show_icons=true)](https://github.com/1552980358)
[![1552980358's most used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=1552980358&layout=compact&langs_count=10)](https://github.com/1552980358)
[![1552980358's coding time](https://github-readme-stats.vercel.app/api/wakatime?username=1552980358)](https://github.com/1552980358)

```Kotlin
class MySelf {
    init {
        val basicInfo = {
            val id = "1552980358"
            val location = "Hong Kong Special Administrative Region, The People's Republic of China"
            val languages = listOf("zh-CN", "en-GB")
            val career = {
                val main = {
                    val name = "Student"
                    val school =  {
                        val type = "University"
                        val schoolName = "The Hong Kong Polytechnic University"
                        val subject = "Electronic and Information Engineering"
                        val department = "Department of Electronic and Information Engineering"
                    }
                }
                val partTime = {
                    val name = "Open-sourced Developer"
                    val platform = "Google Android"
                    val languages = listOf("Kotlin", "XML")
                }
                
            }
            val emails = with(arrayOf("1552980358#qq.com", "qq1552980358#gmail.com")) {
                for ((i, j) in withIndex()) {
                    if (j.contains('#')) {
                        this[i] = j.replace('#', '@')
                    }
                }
                toList()
            }
            
        }
        
        val devInfo = {
            val environment = listOf("Windows 10 x64", "Arch Linux x64", "Ubuntu LTS x64")
            val tools = listOf(
                "Intellij IDEA", "CLion", "Rider","PyCharm",
                "Arduino",
                "Microchip Studio",
                "Visual Studio"
            )
            val languages = listOf("Kotlin", "C", "C++", "Java", "Pascal", "C#", "Python")
            val projects = listOf("MusicPlayer")
        }
    }
}
```
