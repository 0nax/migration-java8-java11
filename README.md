# Migration from Java 8 to Java 11
Code examples to migrate from Java 8 to Java 11.

You can go through the different packages and modify the code to comply with the last version of Java. Don't forget to update first the POM file.

All the portions of code to modify are marked with a TODO.

The code is not perfect but there are plenty of tests, so don't hesitate to play with and modify it :)

## Stream and Optional with an example about renting public electric scooters
A part of this project is about renting electric scooters and bikes with providers, users and juicers.

You would be able to play with streams and optionals on it.

## Unmodifiable collections
Simple cases to have unmodifiable Set, List and Map

## New features for the String class
There's a unit test class to play with these new features.

## New features for file read and write
There's a unit test class to play with these new features.

## New features for Optional class
There's a unit test class to play with these new features.

The examples are not really awesome but they show at least new features.

## Summary about new used features
### From Java 9
* Collections : *List.of*, *Set.of*, *Map.of*
* Optional : *or*, *ifPresentOrElse*
* Scanner class : new method *tokens*
* Modular programming
* Private methods in interfaces

### From Java 10
* New keyword *var* for local variables
* Method *copyOf* for List, Set and Map
* New Collectors : *toUnmodifiableList*, *toUnmodifiableSet*, *toUnmodifiableMap*
* Stream : *ofNullable*, *dropWhile*, *takeWhile*
* Optional : *orElseThrow*

### From Java 11
* String : *isBlank*, *lines*, *strip*, *stripLeading*, *stripTailing*, *repeat*
* Files : *readString*, *writeString*

Enjoy !
