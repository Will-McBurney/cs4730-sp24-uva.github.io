---
layout: default
title: MonoGame
nav_order: 5
---

# MonoGame
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Basic Information

We are using MonoGame 3.8.1 with Microsoft Visual Studio Community 2022

## Links and Official Samples

* [MonoGame Homepage](https://www.monogame.net/)
* [Getting Started with MonoGame](https://docs.monogame.net/articles/getting_started/0_getting_started.html)
* [Official MonoGame Example Projects](https://github.com/MonoGame/MonoGame.Samples)

## Installing MonoGame

__Windows__ 

[Official Instructions @ https://docs.monogame.net/articles/getting_started/1_setting_up_your_development_environment_windows.html](https://docs.monogame.net/articles/getting_started/1_setting_up_your_development_environment_windows.html)

We will want to download the Community 2022 version of VS from the drop-down, but otherwise these instructions from MonoGame are accurate.

__Mac__

_NOTE: Tested on Intel chip_

Follow the same link as above to download Visual Studio 2022

When the installer asks what you’d like to install:

* .NET 
* .NET Multi-platform App UI 
* macOS (Cocoa)

This will take a while.

From the MonoGame github release channel [https://github.com/MonoGame/MonoGame/releases](https://github.com/MonoGame/MonoGame/releases), download `MonoGame.Templates.VSMacExtension_3.8.1.303.mpack`

Once Visual Studio is installed:

* Launch VS
* Go to Visual Studio -> Extensions…
* Click Install from file…
* Select the .mpack downloaded above. 

Clicking through the Oks, it will advise you that there was an error but installed it anyway. This is a known issue [https://github.com/MonoGame/MonoGame/issues/7960](https://github.com/MonoGame/MonoGame/issues/7960).

From the above issue report, the recommended course of action is to enter in the Terminal:

`dotnet new --install MonoGame.Templates.CSharp`

When you open VS and select New, a MonoGame Cross-Platform project template may appear as a Recent option. If not, go to the bottom under Other, then Custom, and select MonoGame Cross-Platform Desktop Application.

Note, after around 30 days, VS will warn you that your license has expired and require you to sign in to your Microsoft account to proceed. Logging in to the SSO for UVA was sufficient for continued access. 

## MonoGame Labs

[MonoGame Lab 1 - BoxBattle](#)