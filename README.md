# DarkAPI
## Adding API to your project
`build.gradle`
### Repository
```gradle
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
```
### Dependence
```gradle
implementation 'com.github.why7ss7why-max:DarkAPI:123'
```

`build.gradle.kts`
### Repository
```gradle
		repositories {
			mavenCentral()
			maven { url = uri("https://jitpack.io") }
		}
```

### Dependence
```gradle
implementation("com.github.why7ss7why-max:DarkAPI:Tag")
```
