# automatic-octo-winner

A Gradle-based Java project with automated CI/CD pipeline.

## Project Structure

```
automatic-octo-winner/
├── src/
│   ├── main/
│   │   └── java/
│   └── test/
│       └── java/
├── build.gradle
├── settings.gradle
└── .github/workflows/
    └── main.yml
```

## Getting Started

### Prerequisites
- Java 11 or higher
- Gradle 7.0 or higher

### Build

```bash
./gradlew build
```

### Run Tests

```bash
./gradlew test
```

### Run Application

```bash
./gradlew run
```

## CI/CD

This project uses GitHub Actions for automated testing and building. See `.github/workflows/main.yml` for workflow configuration.
