# webmatrix-validations #

Simple validation functions for use with WebMatrix / ASP.NET WebPages.

## Comparisons ##

Several methods used to compare any two values of the same type, where the type implements `IComparable`. This includes all built-in numeric types and strings.

## Range Validation ##

A single method (`IsBetween()`) which returns `true` if the passed in value falls between the specified minimum and maximum values (inclusive). Again, this can be used with any type that implements `IComparable`.

## Pattern Matching ##

Several methods used to match strings to common Regex patterns.

