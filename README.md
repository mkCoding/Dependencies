# Dependencies
This repo is for me to reference any dependency I may need in future develpment quickly

## build.gradle (Project level)
<details>
<summary><strong>🧩 Hilt (DI) Plugin - Kapt</strong></summary>

```gradle
id("com.google.dagger.hilt.android") version "2.51.1" apply false
```
</details> 

<!--------------------New Break---------------------->

<details>
<summary><strong>🧩 Hilt (DI) Plugin - KSP</strong></summary>

```gradle
  id("com.google.dagger.hilt.android") version "2.51.1" apply false
  id("com.google.devtools.ksp") version "2.0.21-1.0.27" apply false
```
</details> 


## app/build.gradle (App Level - Plugin)
<details>
<summary><strong>🧩 Hilt (DI) - Kapt Plugin</strong></summary>

```gradle
id ("kotlin-kapt") 
id ("com.google.dagger.hilt.android")
```
</details> 



<!--------------------New Break---------------------->
<details>
<summary><strong>🧩 Hilt (DI) - KSP Plugin</strong></summary>

```gradle
    id("com.google.dagger.hilt.android")
    id("com.google.devtools.ksp")
```
</details> 

## app/build.gradle (App Level - Dependencies)
<details>
<summary><strong>🧩 Hilt (DI) - Kapt / HiltViewModel</strong></summary>

```gradle
// Android Block - Hilt - Kapt
android{
 kapt { correctErrorTypes = true}
}

// Dependencies
implementation("com.google.dagger:hilt-android:2.51.1")
kapt("com.google.dagger:hilt-android-compiler:2.51.1")
implementation("androidx.hilt:hilt-navigation-compose:1.2.0")
```
</details> 

<!--------------------New Break---------------------->

<details>
<summary><strong>🧩 Hilt (DI) - KSP / HiltViewModel</strong></summary>

```gradle
// Android Block - Hilt - KSP
android{
// nothing here
}

// Dependencies
    ksp("com.google.dagger:hilt-android-compiler:2.51.1")
    ksp("androidx.room:room-compiler:2.5.0")

    implementation("androidx.hilt:hilt-navigation-compose:1.2.0")
    implementation("com.google.dagger:hilt-android:2.51.1")
```
</details> 


<!--------------------New Break---------------------->


<details>
<summary><strong>🧠 ViewModel & Lifecycle</strong></summary>

```gradle
implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.8.7")
implementation("androidx.lifecycle:lifecycle-runtime-compose:2.8.7")
implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.8.4")
```
</details>


<!--------------------New Break---------------------->



<details>
<summary><strong>🧠 Retrofit & Network </strong></summary>
  
```gradle
implementation("com.squareup.retrofit2:retrofit:2.11.0")
implementation("com.squareup.okhttp3:logging-interceptor:4.12.0")
```
</details>

<!--------------------New Break---------------------->

<details>
<summary><strong>🧠 GSON </strong></summary>
  
```gradle

//GSON
implementation("com.google.code.gson:gson:2.10.1")
implementation("com.squareup.retrofit2:converter-gson:2.10.0")
```
</details>

<!--------------------New Break---------------------->

<details>
<summary><strong>🧠 OKHttp </strong></summary>
  
```gradle
implementation("com.squareup.okhttp3:okhttp:4.12.0")

```
</details>

<!--------------------New Break---------------------->
<details>
<summary><strong>🧠 Navigation</strong></summary>
  
```gradle
implementation("androidx.navigation:navigation-compose:2.7.7")
```
</details>

<!--------------------New Break---------------------->


<details>
<summary><strong>🧠 JSON Parsing</strong></summary>
  
```gradle
implementation("com.google.code.gson:gson:2.10.1")
```
</details>

<!--------------------New Break---------------------->
<details>
<summary><strong>🧠 Image Loading </strong></summary>
  
```gradle

// Coil library for Compose
implementation("io.coil-kt:coil-compose:2.7.0")
implementation("io.coil-kt:coil-gif:2.7.0")


//Glide
implementation("com.github.bumptech.glide:glide:4.16.0")
```
</details>

<!--------------------New Break---------------------->
<details>
<summary><strong>🧠 Mockito </strong></summary>
  
```gradle
    //Mockito
    testImplementation("junit:junit:4.13.2")
    testImplementation("org.mockito:mockito-core:5.0.0")
    testImplementation("org.mockito.kotlin:mockito-kotlin:5.0.0")
    testImplementation("org.jetbrains.kotlinx:kotlinx-coroutines-test:1.7.3")
```
</details>

    



<!--------------------New Break---------------------->
<!--------------------New Break---------------------->
<!--------------------New Break---------------------->
<!--------------------New Break---------------------->










