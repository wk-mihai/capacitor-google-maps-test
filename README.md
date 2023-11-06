# capacitor-google-maps-test

Code Reproduction for https://github.com/ionic-team/capacitor-plugins/issues/1882
To reproduce the specified issue, just run the _ionic cap run android_ or _npx cap run android_ command. You'll see the following error message:

> FAILURE: Build failed with an exception.

> Execution failed for task ':capacitor-google-maps:compileDebugKotlin'.
> 'compileDebugJavaWithJavac' task (current target is 17) and 'compileDebugKotlin' task (current target is 19)
> jvm target compatibility should be set to the same Java version.
> Consider using JVM toolchain: https://kotl.in/gradle/jvm/toolchain
