# Cheatsheet of Swift 5 updates for app developers
\* Estimated to be used frequently
## Swift 5.0
- Source: https://www.hackingwithswift.com/articles/126/whats-new-in-swift-5-0
- Another good article: https://www.raywenderlich.com/55728-what-s-new-in-swift-5#toc-anchor-015
#### Result type*
Supports Result with success and failure cases
#### Raw Strings*
Easy string literals - supports regex (#"This is a "String""#)
#### String Interpolation
Supports custom string interpolation
#### Dynamic callable types
Swift can work alongside dynamic languages such as python and javascript
#### Enums 
@unknown produces warnings to support enums that can be added in future
#### Try?*
Nested optional from try? is now flattened
#### Integer
Integer multiples can be checked with isMultiple rather than %
#### Dictionary
Added compactMapValues() similar to compactMap on array
## Swift 5.1
- Source: https://www.hackingwithswift.com/articles/182/whats-new-in-swift-5-1
#### Structs*
Synthesized memberwise initializers - providing values for properties with default parameter values is optional in initializers
#### Functions*
Implicit return for single expression - no need to mention return keyword in single expression function just like closures
#### Self
Self can refer to dynamic types (subclasses) to get current type properties
#### Return types
Opaque return types - some keyword - Allows better comparison of return values of function without exposing actual type
#### Subscripts
Static or class subscripts - subscripts can be added on types
#### Optional none case
warnings are shown when none is used in enums
#### Switch
Now we can match optional enum with non-optional cases in switch
#### Ordered Collection
collection diffing - calculate difference between two ordered collections
#### Arrays
Uninitialized arrays - new API to create uninitialized array
## Swift 5.2
- Source: https://www.hackingwithswift.com/articles/212/whats-new-in-swift-5-2
#### Keypath Expressions*
Keypath expression as functions - can use keypath(\.root.value) in case of function such as (root) -> value
#### Callable values
Statically callable values - callAsFunction()
#### Subscripts
Default arguments - subscripts can have default arguments for any parameter
#### Lazy Sequence
lazy sequence order of filtering is reversed
#### Diagnostics
Better error messages for swiftui
## Swift 5.3
- Source: https://www.hackingwithswift.com/articles/218/whats-new-in-swift-5-3
#### Catch clause*
Multi-pattern catch clause - single catch block can match multiple patterns (no need of switch in catch clause)
#### Trailing closures* (swiftui)
Multiple trailing closures - supports multiple trailing closure (drops label of first closure)
#### Enums*
Comparable enums - enums will be synthesized to be comparable on conformance (<, >)
#### self*
self is optional in closures (can omit self in closure that does not result in retain cycles)
#### main
@main can be used for program entry point instead of main.swift file
#### Generics
Where clause on contextually generic declarations
#### Enums
Enum cases can match protocol requirements easily
#### didSet
made efficient
#### Float16
new Float16 type commonly used in graphics programming and machine learning
#### Swift package manager
Allows resources, localized resources, binary dependencies, conditional target dependencies, 

