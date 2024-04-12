
![Typescript_logo_2020 svg](https://github.com/elic4vet/Tsc-project/assets/86532060/5f214531-3284-468a-aa22-4730276dbd1d)
# Typescript  
- [Introduction](#introduction)
  - [Statically typed](#statically-typed)
  - [Dynamically typed](#dynamically-typed)
- [Compiler](#typescript-compiler)
  - [Installing compiler](#installing-compiler)
- [Debugging](#typescript-compiler)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


# Introduction to Typescript 

TypeScript is a programming language that adds static type-checking to JavaScript.

## Statically Typed
A statically typed language is a language (such as Java, C, or C++) where variable types are known at compile time. In most of these languages, 
types must be expressly indicated by the programmer; in other cases (such as OCaml), type inference allows the programmer to not indicate their variable types.

source: https://developer.mozilla.org/en-US/docs/Glossary/Static_typing 

## Dynamically Typed 

Dynamically typed languages are those (like JavaScript, Python, and Ruby ) where the interpreter assigns variables a type at runtime based on the variable's value at the time.

source: https://developer.mozilla.org/en-US/docs/Glossary/Dynamic_typing


# TypeScript Compiler (tsc)
tsc is the TypeScript Compiler. It converts the TypeScript files (.ts or .tsx ) and compiles them into JavaScript code (.js files) that a JavaScript runtime can execute.

## Installing Compiler

Npm package: https://www.npmjs.com/package/typescript?activeTab=versions

```
npm i -g typescript 
```

Check the installed edition: 
```
tsc -v
```
 
# Debugging - `tsconfig.json` 
```
tsc --init

```

to be continued.... 


# Acknowledgments

* [Everyday types](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html)
* [The basics](https://www.typescriptlang.org/docs/handbook/2/basic-types.html)
* [TypeScript](https://developer.mozilla.org/en-US/docs/Glossary/TypeScript)
* [Compile TypeScript code](https://learn.microsoft.com/en-us/visualstudio/javascript/compile-typescript-code-npm?view=vs-2022)




