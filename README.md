# pd-for-android-studio
[pd-for-android](https://github.com/libpd/pd-for-android) updated for ease of use with android studio projects

just clone this repo into your project folder, and add into settings.gradle:

```
include(':PdCore')
```

and build.gradle:

```
dependencies {
    ...
    compile project(':PdCore')
}
```
