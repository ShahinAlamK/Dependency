//project module
id("com.google.dagger.hilt.android") version "2.48.1" apply false

//build module
kotlin("kapt")
    id("com.google.dagger.hilt.android")


//Statuts Bar Controller
implementation("com.google.accompanist:accompanist-systemuicontroller:0.35.0-alpha")

//Navigation
implementation("androidx.navigation:navigation-compose:2.7.6")

//dagger hilt
implementation("com.google.dagger:hilt-android:2.48.1")
kapt("com.google.dagger:hilt-android-compiler:2.48")
kapt("androidx.hilt:hilt-compiler:1.1.0")

//Hilt Navigation
implementation("androidx.hilt:hilt-navigation-compose:1.1.0")

//kotlin coroutines
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.3")
implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:1.7.3")
