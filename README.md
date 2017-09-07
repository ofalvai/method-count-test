# Method Count Test project

## Results

### New, empty project

Dependencies:

```
implementation 'com.android.support:appcompat-v7:26.0.2'
implementation 'com.android.support.constraint:constraint-layout:1.0.2'
implementation 'com.android.support:design:26.0.2'
```

Dexcount output:

```
Total methods in app-debug.apk: 22367 (34.13% used)
Total fields in app-debug.apk:  14970 (22.84% used)
Total classes in app-debug.apk:  2542 (3.88% used)
```


### Adding Kotlin

Dependencies:

```
implementation 'org.jetbrains.kotlin:kotlin-stdlib-jre7:1.1.4-3'
implementation 'com.android.support:appcompat-v7:26.0.2'
implementation 'com.android.support.constraint:constraint-layout:1.0.2'
implementation 'com.android.support:design:26.0.2'
```

Dexcount output:

```
Total methods in app-debug.apk: 28483 (43.46% used)
Total fields in app-debug.apk:  15709 (23.97% used)
Total classes in app-debug.apk:  3163 (4.83% used)
```

Method count increased by **6116**