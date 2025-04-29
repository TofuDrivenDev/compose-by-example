# [Compose by Example](https://tofudrivendev.github.io/compose-by-example/)

[![Deploy Wasm 🌐 ](https://github.com/TofuDrivenDev/compose-by-example/actions/workflows/deploy.yml/badge.svg)](https://github.com/TofuDrivenDev/bank-of-canada-forex/actions/workflows/deploy.yml)

Compose by Example is an interactive introduction to [Jetpack Compose](https://developer.android.com/develop/ui/compose/components) and [Compose Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/).

What stands out from the official docs is that the example code you see in each section is exactly what is executed on the webiste.
This is possible because Compose by Example is written in Compose Multiplatform and then compiled into WasmJS.
Because it is interactive, you can click and type in the examples to learn how the code affects the UI.

## Features

- Examples are interactive: Users can play with the examples directly in the website to learn how the code changes the UI.
- Examples are complete programs: Users can copy & paste the code in their own IDE and have it run locally.
- Live state observation: Examples which feature state changes print their state similar to debug mode.

## Issues

- HUGE binary size: The Wasm bundle is 13MB! It will take some time to load on slow networks. (For reference, an empty project from [Kotlin Multiplatform Wizard](https://kmp.jetbrains.com/) compiles into a 9MB Wasm bundle.)
- Slow startup time: It may feel like the app is frozen when you first visit the site. It's just loading the Wasm bundle as the entire bundle needs to be loaded until first paint.
- More topics: I aim to cover more topics topics such as Animations, Modifiers, and the remaining Components.

<img width="912" alt="demo" src="https://raw.githubusercontent.com/TofuDrivenDev/compose-by-example/refs/heads/main/doc/demo.png" />

