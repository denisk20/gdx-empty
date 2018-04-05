# To see the bug:

Run `./gradlew desktop:dependencies --stacktrace`

If you run `./gradlew clean desktop:dependencies` it actually works.

If you change android gradle plugin version from `3.1.0` to `3.0.0` it works.
