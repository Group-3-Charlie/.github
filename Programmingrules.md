# Code Style Guide

## General information

Main programming Language: JavaScript

The source code must be JSe6 compliant.

## Header Files
The Js files have the .js extension and are structured in a way that makes them easy to read and understand.
### Component’s names should be written using pascal case:
```JavaScript
Header.js
HeroBanner.js
CookieBanner.js
BlogListing.js
```
### Non-components should be written using camel case:
```JavaScript
myUtilityFile.js
cookieHelper.js
fetchApi.js
```
## Unit test files should use the same name as its corresponding file:
```JavaScript
CookieBanner.js
CookieBanner.test.js

fetchData.js
fetchData.test.js
```
### Function should be written using camel case:
```JavaScript
doSomething();
useEffect();
```
## Attribute name should be camel case:
```JavaScript
className
onClick
```

## Indentation
An indentation consists of 4 spaces or a tab of 4 spaces. Make sure to configure your IDE to apply this convention.


## Space
- Make sure to add a space after each comma in methods arguments definition.
    - ✅ ```dealEffect(user, actual_targets)```
    - ❌ ```dealEffect(user,actual_targets)```
- Make sure to add a space between an operator and an expression.
    - ✅ ```a = b + c```
    - ❌ ```a=b+c```
