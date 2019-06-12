# Chapter 3 - Introduction to C# App Programming

### 1. Comments

#### Single Line
Use `//` then type comment
##### Example
```cs
// Comment here 
```
#### Multi-line
Use `/* */` to start and to end
##### Example
```cs
/* Comment here first line
   another line for commenting */
```
---
### 2. `using` Directive

A directive that tells the compilier where to look for a class that's used in this app.  These classes are organized under **namespaces**.

##### Example
```cs
using System;
```
---
### 3. Blank Lines and Whitespace

Line 4 is simply a blank line. Blank lines and space characters make code easier to read, and together with tab characters are known as whitespace. Space characters and tabs are known specifically as whitespace characters. Whitespace is ignored by the compiler.

---
### 4. Class Declaration
Every app consists of at least one class declaration that’s defined by you—the programmer. These are known as user-defined classes. The class keyword introduces a class declaration and is immediately followed by the **class name**. By convention, all class names begin with a capital letter and capitalize the first letter of each word they include.  This is called **camel case**.  When the first letter is capitalized, it’s known as **Pascal Case**.
##### Example of a Class Declaration
```cs
class Welcome1
```
##### Example of a camelCase
```cs
void nameSomethingHere
```
##### Example of a Pascal Case
```cs
class FoodTesterMax
```
---
### Keywords and Contectual Keywords
ADD CHART HERE

---
### Class Declaration's File Name
A class declaration’s file name is usually the class name followed by the .cs file-name extension, though this is not required.

##### Example
```cs
FileName.cs
```
