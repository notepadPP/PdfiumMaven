# PdfiumAndroid16KB Maven Repository

This repository hosts the PdfiumAndroid16KB AAR library as a Maven package.

## Version 2.0.0

- **Group ID**: `com.github.chiragthummar`
- **Artifact ID**: `PdfiumAndroid16KB`
- **Version**: `2.0.0`
- **Description**: 16KB page size support for pdfium-android (Google Play Android 15+ compatibility)

## Usage

Add the repository to your `settings.gradle.kts`:

```kotlin
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { 
            url = uri("https://raw.githubusercontent.com/notepadPP/Readerbooks-PdfiumMaven/main/maven")
        }
    }
}
```

Add the dependency to your `app/build.gradle.kts`:

```kotlin
dependencies {
    implementation("com.github.chiragthummar:PdfiumAndroid16KB:2.0.0")
}
```

## License

See the [original PdfiumAndroid16KB license](https://github.com/chiragthummar/PdfiumAndroid16KB/blob/master/LICENSE).