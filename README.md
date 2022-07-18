# MTLRaytracingSampleSwift
A Swift port of Apple's Metal raytracing sample originally written in Objective-C

https://developer.apple.com/documentation/metal/metal_sample_code_library/accelerating_ray_tracing_using_metal?language=objc

This version only supports macOS, and will only work on Apple Silicon (although it would be easy to make it work on Intel by changing storage modes from shared to managed and adding the didModifyRange calls from the original sample)
