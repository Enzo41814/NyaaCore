## Use as dependency in Gradle

```
repositories {
    maven {
        name 'NyaaCore'
        url 'https://raw.githubusercontent.com/NyaaCat/NyaaCore/maven-repo'
    }
}

dependencies {
    compile('cat.nyaa:nyaacore:2.0-SNAPSHOT') {
        transitive = false
    }
}
```