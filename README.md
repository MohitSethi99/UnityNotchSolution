<h1 align="left" style="border-bottom: none;">
  <a href="https://github.com/MohitSethi99/UnityNotchSolution/">Unity Notch Solution</a>
</h1>

[![Build Status](https://github.com/MohitSethi99/UnityNotchSolution/workflows/build/badge.svg)](https://github.com/MohitSethi99/UnityNotchSolution/actions?workflow=build)
[![CodeFactor](https://www.codefactor.io/repository/github/mohitsethi99/unitynotchsolution/badge)](https://www.codefactor.io/repository/github/mohitsethi99/unitynotchsolution)

<p align="left">
  <img alt="platforms" src="https://img.shields.io/badge/platform-Unity-blue?style=flat-square"/>
  <img alt="GitHub" src="https://img.shields.io/github/license/MohitSethi99/UnityNotchSolution?color=blue&style=flat-square">
  <img alt="size" src="https://img.shields.io/github/repo-size/MohitSethi99/UnityNotchSolution?style=flat-square"/>
  <br/>
</p>

## Prerequisites

Packages : Device Simulator (For testing inside editor)


## Features

- Easy To Use Notch Solution
- Plug and Play

<p align="center">
    <img height="360" src="Documentation/NotchIssue.jpg" alt="NotchIssue" />
    <br>
    Notch issue
</p>

<p align="center">
    <img height="360" src="Documentation/NotchSolution.jpg" alt="NotchSolution" />
    <br>
    Notch Solution
</p>


## Setting Up
- Grab the latest release from [Here](https://github.com/MohitSethi99/UnityNotchSolution/releases) and import it.
- Make a new gameObject as the child of Background image in the panel and rename it to SafeAreaHolder.
- Attach The SafeArea Script To SafeAreaHolder gameObject.
- Shift all your UI gameObjects inside the SafeAreaHolder gameObject making them the children of SafeAreaHolder.
- Open device simulator and switch to any of the notched devices to test.
- See the below config for more clarification or open the Demo scene.

<p align="center">
    <img height="360" src="Documentation/Config.jpg" alt="Config" />
    <br>
    Config
</p>
