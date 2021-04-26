# LockedBitmap
A wrapper around the LockedBitmap class, with some useful helper methods. This package can be used when the general Bitmap class is not performant enough, in cases such as image searching, or manipulating a single image many times. 

## Table of contents
* [Installation](#installation)
* [Usage](#usage)
* [Methods](#methods)

## Installation
To install Locked Bitmap, from package manager, run the following: 
``` 
    Install-Package LockedBitmap
```

## Usage
The class `LockedBitmap.cs` does most of the heavy lifting. You can either new up an instance of the `LockedBitmap`, or, add a using reference to `LockedBitmap.Extensions` in your file, and this will give you a fluent interface over the `Bitmap` type with the Extension methods seen in `Extensions/FluentConversions.cs`.

## Methods

### Transformation
#### Crop
#### Resize
#### GreyScale
#### ToBinaryImage


### Image Searching

#### DoesImageExist
#### GetAllOccurences