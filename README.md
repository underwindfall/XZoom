# OpenSourceTemplate (ANDROID)
This repository can be used as a template to create new GitHub repositories for Kotlin/Android libraries.

### Code Formatting

```gradle
./gradlew spotlessApply
```

*Make sure you update [spotless.license.kt](spotless/copyright.kt) author info!* Other settings for this plugin can be tweaked in [spotless/spotless.gradle](spotless/spotless.gradle).

### Check if Dependencies Are Up-to-Date

```gradle
./gradlew dependencyUpdates
```
Settings can be tweaked for this plugin within [versions_plugin_config.gradle](version_plugin_config.gradle).

### Publishing the Library to Bintray -> jCenter

This repository is setup to automatically publish to Bintray when you create a new release from
GitHub. You can find more in [release.yml](.github/workflows/release.yml)
