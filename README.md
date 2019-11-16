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
* [Lazy var](#private-var)
* [Private lazy var](#private-lazy-var)
* [Class template](#class-template)
--------
### Static let
Prefix | Description
--- | ---
sl | Creates a static let

<details>
<summary>Example</summary>

```swift
static let <#name#> = <#value#>
```
</details>

### Static let CGFloat
Prefix | Description
--- | ---
slf | Creates a static let of CGFloat type

<details>
<summary>Example</summary>

```swift
static let <#name#>: CGFloat = <#value#>
```
</details>

### Private enum constants
Prefix | Description
--- | ---
pec | Creates a private enum with name Constants

<details>
<summary>Example</summary>

```swift
private enum Constants {
    <#variables#>
}
```
</details>

### Private enum layouts
Prefix | Description
--- | ---
pec | Creates a private enum with name Layouts

<details>
<summary>Example</summary>

```swift
private enum Layouts {
    <#variables#>
}
```
</details>

### Private var
Prefix | Description
--- | ---
lv | Creates a lazy variable

<details>
<summary>Example</summary>

```swift
lazy var <#name#>: <#type#> = {
    <#code#>
}()
```
</details>

### Private lazy var
Prefix | Description
--- | ---
plv | Creates a private lazy variable

<details>
<summary>Example</summary>

```swift
private lazy var <#name#>: <#type#> = {
    <#code#>
}()
```
</details>

### Class template
Prefix | Description
--- | ---
cls | Creates a class template with marks

<details>
<summary>Example</summary>

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
</details>
