[![Logo](https://github.com/Uroria/.github/blob/main/github_banner.png?raw=true)](https://uroria.com)

# Curepur
[![Maven Central](https://img.shields.io/maven-central/v/com.uroria.stable/curepur-api?label=stable&style=for-the-badge&logo=apachemaven&logoColor=%236CEFF0&labelColor=%232D2D2D&color=%233881d9)](https://central.sonatype.com/artifact/com.uroria.stable/curepur-api)
[![Maven Central](https://img.shields.io/maven-central/v/com.uroria.latest/curepur-api?label=latest&style=for-the-badge&logo=apachemaven&logoColor=%236CEFF0&labelColor=%232D2D2D&color=%233881d9)](https://central.sonatype.com/artifact/com.uroria.latest/curepur-api)
[![Discord](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscord.com%2Fapi%2Finvites%2FRGX8rPshFG%3Fwith_counts%3Dtrue&query=%24.approximate_presence_count&style=for-the-badge&logo=discord&logoColor=%236CEFF0&labelColor=%232D2D2D&color=%233881d9&label=Users%20Online)](https://dc.uroria.com/)

A [Purpur](https://github.com/purpurmc/purpur) fork aiming to provide a better experience in maintaining, developing and 
building minecraft networks.

## Installation
- Visit the [Releases page](https://github.com/uroria/core/releases)
- Download the **latest stable release** `curepur-server-x.x.x-Rx.x.jar`
- Copy it in your servers folder
- Launch the `curepur-server-x.x.x-Rx.x.jar` like traditional minecraft servers
- Configure it via the configuration files inside the `configs` directory
- Restart the server


## Usage
To use the api for developing your own plugins add the following
dependency to your project.

**Replace `$VERSION` with your Curepur servers version.**

### Gradle (Groovy)
```groovy
// build.gradle
repositories {
    mavenCentral()
}

dependencies {
    compileOnly 'com.uroria.stable:curepur-api:$VERSION'
}
```

### Gradle (Kotlin)
```kotlin
// build.gradle.kts
repositories {
    mavenCentral()
}

dependencies {
    compileOnly("com.uroria.stable:curepur-api:$VERSION")
}
```

### Maven
```xml
<dependencies>
    <dependency>
        <groupId>com.uroria.stable</groupId>
        <artifactId>curepur-api</artifactId>
        <version>$VERSION</version>
        <scope>system</scope>
    </dependency>
</dependencies>
```

## License
This project is licensed under the [**MIT License**](LICENSE).