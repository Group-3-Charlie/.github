# Code Style Guide

## General information

Main programming Languages: JavaScript, Python.

The source code must be JSe6 and Python3.12 compliant.

## JavaScript

### Header Files
The Js files have the .js extension and are structured in a way that makes them easy to read and understand.
#### Component’s names should be written using pascal case:
```JavaScript
Header.js
HeroBanner.js
CookieBanner.js
BlogListing.js
```
#### Non-components should be written using camel case:
```JavaScript
myUtilityFile.js
cookieHelper.js
fetchApi.js
```
### Unit test files should use the same name as its corresponding file:
```JavaScript
CookieBanner.js
CookieBanner.test.js

fetchData.js
fetchData.test.js
```
#### Function should be written using camel case:
```JavaScript
doSomething();
useEffect();
```
### Attribute name should be camel case:
```JavaScript
className
onClick
```

## Python

### Header Files
The python files have the .py extension and are structured in a way that makes them easy to read and understand.
#### Module’s names should be written using snake case:
```Python
header.py
hero_banner.py
cookie_banner.py
blog_listing.py
```

#### Class’s names should be written using pascal case:
```Python
class Header:
    pass

class HeroBanner:
    pass
```

#### Function should be written using snake case:
```Python
do_something()
use_effect()
```

#### Variable name should be snake case:
```Python
my_variable
my_list
my_dict
```

## Naming Conventions
- Use descriptive names for variables, functions, and methods.
- Use all caps for constants.

## Comments
- Use comments to explain the code when necessary.
- Comments should be written in English.
- Comments should be concise and to the point.

## Indentation
An indentation consists of 4 spaces or a tab of 4 spaces. Make sure to configure your IDE to apply this convention.


## Space
- Make sure to add a space after each comma in methods arguments definition.
    - ✅ ```dealEffect(user, actual_targets)```
    - ❌ ```dealEffect(user,actual_targets)```
- Make sure to add a space between an operator and an expression.
    - ✅ ```a = b + c```
    - ❌ ```a=b+c```
