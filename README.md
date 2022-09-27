# AuthTest

#Introduction
AuthSafe sdk helps us to detect suspicious activities in real time and provides device fingerprinting, behavioral analysis, and client-side event monitoring. 

#Requirements

minSdk version = 21 

Internet permission 

Location permission (optional) 

ACCESS_FINE_LOCATION, 

ACCESS_COARSE_LOCATION  

Step 1 >  Add the JitPack repository to your build file

```gradle

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
Step 2 > Add the dependency

```gradle
dependencies {
# AuthSafe

Step 1 >  Add the JitPack repository to your build file

```gradle

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
Step 2 > Add the dependency

```gradle
dependencies {
	        implementation 'com.github.Ashishchidhava:Library-Task:Tag'
	}
  ```
  
Step 3 > Add secret key in your manifest file
  ```
  <meta-data 

    android:name="auth_safe_secret_key" 

    android:value="@string/auth_secret" /> 
  ```
  
  #Java
  
  // Place the below in your application class onCreate method 

```
AuthSafe.configure(this) 
```

