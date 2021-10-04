---
layout: ../../layouts/project.astro
title: Unique Password Generator
font: black
client: Self
published_at: 2020-03-02 00:00:00
img: /assets/pictures/passwordGenerator.png
description: A unique password generator.
tags:
  - Html
  - Javascript
---

Link to deployed website https://jocecode.github.io/Password-Generator/

# Password Generator

## Description

This project features a Password generator that asks the user "how long do you want your password". It MUST BE BETWEEN 8-128 characters long. If the user DOES NOT enter a NUMBER value between 8-128 or a NUMBER, it will PROMPT AGAIN asking "how long do you want your password" until it's a NUMBER and the value is between 8-128. It then asks 4 more questions asking if they want the password to have at least one NUMBER, at least one SPECIAL CHARACTER, at least one UPPERCASE LETTER, and or at least one LOWERCASE LETTER. If the user does not pick one of the selections (NUMBER, SPECIAL CHARACTER, UPPERCASE LETTER, LOWERCASE LETTER) it will repeat the prompt again until at least one is selected. When the user clicks the generate password button a Password with the selected criteria (NUMBER, SPECIAL CHARACTER, UPPERCASE LETTER, LOWERCASE LETTER, LENGTH) will appear. The generate password button then becomes disabled and the displayed password can be copied and pasted.
