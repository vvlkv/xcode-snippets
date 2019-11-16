# xcode-snippets
Personal snippets for xCode IDE
## Description
This repo contains:
* Code snippets for xCode IDE (*.codesnippet files)
* Two scripts for moving snippets between cloned repo and xCode folder where snippets are placed:
    * Import: Moves snippets from existing folder to xCode;
    * Export: Moves snippets from xCode to existing folder.
## Installation
1. Clone this repository into any folder;
2. Run script **Import**;
3. Restart xCode.
## Snippets
* [Static let](#static-let)
* [Static let CGFloat](#static-let-cgfloat)
* [Private enum constants](#private-enum-constants)
* [Private enum layouts](#private-enum-layouts)
* [Class template](#class-template)
--------
### Static let
Prefix | Description
--- | ---
sl | Creates static let
#### Example
```swift
static let <#name#> = <#value#>
```
### Static let CGFloat
Prefix | Description
--- | ---
slf | Creates static let of CGFloat type
#### Example
```swift
static let <#name#>: CGFloat = <#value#>
```
### Private enum constants
Prefix | Description
--- | ---
pec | Creates private enum with name Constants
#### Example
```swift
private enum Constants {
    <#variables#>
}
```
### Private enum layouts
Prefix | Description
--- | ---
pec | Creates private enum with name Layouts
#### Example
```swift
private enum Layouts {
    <#variables#>
}
```
### Class template
Prefix | Description
--- | ---
cls | Creates a class template with marks
#### Example
```swift
class <#name#>: <#super class#> {

    // MARK: - Variables

    <#private let block#>

    <#private var block#>

    <#public let block#>

    <#public var block#>

    // MARK: - Initializers

    <#initializers block#>

    // MARK: - Overrides

    <#override functions block#>

    // MARK: - Public functions

    <#public functions block#>

    // MARK: - Private functions

    <#private functions block#>
}
```
