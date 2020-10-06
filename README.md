[![Release](https://jitpack.io/v/evilthreads669966/wakescope.svg)](https://jitpack.io/#evilthreads669966/wakescope)&nbsp;&nbsp;[![API](https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=plastic)](https://android-arsenal.com/api?level=14)
# WakeScope
### An Android library that gives you a scoping function that keeps your processor awake.
## User Instructions
1. Add the JitPack repository to your project's build.gradle
```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
2. Add the dependency to your app's build.gradle
```gradle
dependencies {
        implementation 'com.github.evilthreads669966:wakescope:1.0'
}
```
3. Subclass WakeService and override Intent.doWork()
```kotlin
wakeScope {
    //do work
}
```
## License
```
Copyright 2020 Chris Basinger

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
