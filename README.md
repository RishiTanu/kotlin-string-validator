# StringValidator

A lightweight Kotlin library for validating common strings and user input in Android applications.

## Installation

### JitPack

Add JitPack to the repositories in your root Gradle configuration:

```groovy
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```

After a version is published, add the library to your app module. Replace `USERNAME`, `StringCheck`, and `TAG` with the GitHub account, repository, and release tag:

```groovy
dependencies {
    implementation 'com.github.USERNAME:StringCheck:TAG'
}
```

## Usage

The validator API is planned for Version 1. Usage examples will be added when the first methods are implemented and their names and behavior are finalized.

## Version 1 methods

Version 1 is planned to provide the following 20 methods. Each method will return a Boolean indicating whether the input meets the check described.

| Method | Description |
| --- | --- |
| `isEmail` | Checks whether a string has a valid email address format. |
| `isStrongPassword` | Checks whether a password meets the library's documented strength rules. |
| `isUrl` | Checks whether a string has a valid URL format. |
| `isIndianPhoneNumber` | Checks whether a string matches the supported Indian phone number format. |
| `isBlank` | Checks whether a string is empty or contains only whitespace. |
| `isEmpty` | Checks whether a string has zero characters. |
| `isAtLeastLength` | Checks whether a string meets a minimum length. |
| `isAtMostLength` | Checks whether a string stays within a maximum length. |
| `isWithinLength` | Checks whether a string length falls within a minimum and maximum. |
| `isAlpha` | Checks whether a string contains only letters. |
| `isAlphanumeric` | Checks whether a string contains only letters and digits. |
| `isNumeric` | Checks whether a string contains only digits. |
| `isInteger` | Checks whether a string represents an integer. |
| `isDecimal` | Checks whether a string represents a decimal number. |
| `isBoolean` | Checks whether a string represents a boolean value. |
| `isIPAddress` | Checks whether a string is a valid IP address. |
| `isBase64` | Checks whether a string uses valid Base64 encoding. |
| `isLowercase` | Checks whether all letters in a string are lowercase. |
| `isUppercase` | Checks whether all letters in a string are uppercase. |
| `containsSubstring` | Checks whether a string contains a specified substring. |

## License

License details will be added before the project is published.
