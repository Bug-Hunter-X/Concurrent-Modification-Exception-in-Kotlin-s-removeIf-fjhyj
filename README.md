This repository demonstrates a common, yet often subtle, bug in Kotlin when using the `removeIf` function on a mutable list. The code attempts to remove even numbers, but due to concurrent modification, it doesn't always produce the correct result.

The solution showcases a safer approach to modify a list while iterating.