# EPUB test book

Sample EPUB test book built with [epub-gradle-plugin](https://github.com/jmbe/epub-gradle-plugin)

## Using

|                           | Command                       |
|---------------------------|-------------------------------|
| Assemble book once        | `./gradlew epub`              |
| Start build in watch mode | `./gradlew epub --continuous` |
| Create ncx file           | `./gradlew ncx`               |
| Rebuild                   | `./gradlew clean epub`        |

The assembled book will be placed in the `build` directory.

## Adding additional books

1. Add unzipped book contents as directory.
2. Edit `settings.gradle` and include that directory.
