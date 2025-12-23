# Day 08 – Cross Site Scripting (XSS) – Visual Diagram

## Normal Website Behavior

```
User Input
|
v
Website
|
v
Displayed Safely

```
---

## XSS Concept (High Level)

```
User Input
|
v
Website (No Filtering)
|
v
Script Runs in Browser

```
---

## Impact of XSS

```
Injected Script
|
v
Runs in User Browser
|
v
Session or Data Risk

```
---

## Secure Handling

```
User Input
|
v
Proper Encoding
|
v
Safe Output
```
