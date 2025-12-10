# Dependencies
This repo is for me to reference any dependency I may need in future develpment quickly

## build.gradle (Project level)
<details>
<summary><strong>🧩 Hilt (DI) Plugin</strong></summary>

```gradle
id("com.google.dagger.hilt.android") version "2.51.1" apply false
```
</details> 


## app/build.gradle (App Level - Plugin)
<details>
<summary><strong>🧩 Hilt (DI) Plugin</strong></summary>

```gradle
id ("kotlin-kapt") 
id ("com.google.dagger.hilt.android")
```
</details> 


## app/build.gradle (App Level)
<details>
<summary><strong>🧩 Hilt (DI) / HiltViewModel</strong></summary>

```gradle
// Android Block - Hilt
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
<summary><strong>🧠 OKHttp </strong></summary>
  
```gradle
implementation("com.squareup.okhttp3:okhttp:4.12.0")

```
</details>

<!--------------------New Break---------------------->
<details>
<summary><strong>🧠 OKHttp </strong></summary>
  
```gradle
implementation("androidx.navigation:navigation-compose:2.7.7")

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
<!--------------------New Break---------------------->
<!--------------------New Break---------------------->
<!--------------------New Break---------------------->
<!--------------------New Break---------------------->










