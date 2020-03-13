# DHook
_DHook is a WIP lightweight ARM trampoline hook, currently being developed for ARM, planned to be extended to Thumb2 & ARM64_


## Overall Idea (Note that it will eventually be ported to B/BX calls depending on the distance between the original function and the detoured one  ) 📌

![Logic](https://i.imgur.com/TAWoT4u.png)

## Build ⚙️

```
cd jni
ndk-build
```
## Usage 📋
```
check usage over at /jni/entry_point.cpp
```
## TO-DO 📄
* Support Thumb2 and ARM64
* Un-Hook Functionality

## References ✒️
* [ARM Instruction set](https://iitd-plos.github.io/col718/ref/arm-instructionset.pdf)

## Credits
* Delshire (@Reversive)
