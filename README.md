# uareu

Example use of U.are.U 4500B scanner on Android.

To use, ensure the bintray dependencies are added.

In the project's build.gradle:
```Gradle
allprojects {
    // ..
    repositories {
        // ..
        maven { url 'https://dl.bintray.com/shodgson/uareu4500reader' }
    }
}
```

In the app's build.gradle:
```Gradle
dependencies {
    compile fileTree(dir: 'libs', include: ['*.jar'])
    testCompile 'junit:junit:4.12'
    compile 'com.android.support:appcompat-v7:23.4.0'
    compile 'asia.kanopi.tools:fingerscan:0.1'
}
```

Steven Hodgson
steven@kanopi.asia
