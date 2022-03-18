# Bhai-Lang Rough Work

██████╗░██╗░░██╗░█████╗░██╗██╗░░░░░░█████╗░███╗░░██╗░██████╗░
██╔══██╗██║░░██║██╔══██╗██║██║░░░░░██╔══██╗████╗░██║██╔════╝░
██████╦╝███████║███████║██║██║░░░░░███████║██╔██╗██║██║░░██╗░
██╔══██╗██╔══██║██╔══██║██║██║░░░░░██╔══██║██║╚████║██║░░╚██╗
██████╦╝██║░░██║██║░░██║██║███████╗██║░░██║██║░╚███║╚██████╔╝
╚═════╝░╚═╝░░╚═╝╚═╝░░╚═╝╚═╝╚══════╝╚═╝░░╚═╝╚═╝░░╚══╝░╚═════╝░

> It's rough work of 'Bhai-Lang', a toy programing language

## How to run this project

```bash
npm run phone
```

## Resources

1. ['Bhai Lang - GitHub'](https://github.com/DulLabs/bhai-lang)
2. ['Bhai Lang - Playground'](https://bhailang.js.org/)
3. ['Vs code extension'](https://marketplace.visualstudio.com/items?itemName=BrijeshBumrela.bhailang-extension)

## Documentation

### General

`hi bhai` is the entrypoint for the program and all program must end with `bye bhai`. Anything outside of it will be ignored.

```
This will be ignored

hi bhai
 // Write code here
bye bhai

This too
```

### Variables

Variables can be declared using `bhai ye hai`.

```
hi bhai
 bhai ye hai a = 10;
 bhai ye hai b = "two";
 bhai ye hai c = 15;
 a = a + 1;
 b = 21;
 c *= 2;
bye bhai
```

### Types

Numbers and strings are like other languages. Null values can be denoted using `nalla`. `sahi` and `galat` are the boolean values.

```
hi bhai
 bhai ye hai a = 10;
 bhai ye hai b = 10 + (15*20);
 bhai ye hai c = "two";
 bhai ye hai d = 'ok';
 bhai ye hai e = nalla;
 bhai ye hai f = sahi;
 bhai ye hai g = galat;
bye bhai
```

### Built-ins

Use `bol bhai` to print anything to console.

```
hi bhai
  bol bhai "Hello World";
  bhai ye hai a = 10;
  {
    bhai ye hai b = 20;
    bol bhai a + b;
  }
  bol bhai 5, 'ok', nalla , sahi , galat;
bye bhai
```

### Conditionals

Bhailang supports simple if else construct , `agar bhai` block will execute if condition is `sahi` and `warna bhai` block will execute if condition is `galat`.

```
hi bhai
 bhai ye hai a = 10;
 agar bhai (a < 25) {
    bol bhai "a is less than 25";
 } warna bhai {
    bol bhai "a is greater than or equal to 25";
 }
bye bhai
```

### Loops

Statements inside `jab tak bhai` blocks are executed as long as a specified condition evaluates to `sahi`. If the condition becomes `galat`, statement within the loop stops executing and control passes to the statement following the loop. Use `bas kar bhai` to break the loop and `agla dekh bhai` to continue within loop.

```
hi bhai
 bhai ye hai a = 0;
 jab tak bhai (a < 10) {
  a += 1;
  agar bhai (a == 5) {
   bol bhai "andar se bol bhai ", a;
   agla dekh bhai;
  }
  agar bhai (a == 6) {
   bas kar bhai;
  }
  bol bhai a;
 }
 bol bhai "done";
bye bhai
```