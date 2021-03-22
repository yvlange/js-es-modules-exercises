# Exercise 1: ES-Modules Syntax

Your goal is to refactor (re-organize the code without changing functionality) the file `main.js`.

Inside this file we have some functions defined: `sum`, `substract`, `divide` and `multiply`

1. Move the functions to the file `lib/math.js`
2. Export the functions from that file:
   1. `sum` should be the `default` export
   2. The rest of the functions should be `named` exports
3. In the file `main.js`, import the functions from the `lib/math.js` module.
4. Verify that the calls to `console.log` are working and displaying the same results as before moving the code.
5. Extra:

- Export a variable from the `math.js` module and import it in the `main.js` file, renaming it to a different name using the `as` keyword.
- Log the variable to the console, to verify it's working.

6. Questions:

- How can I import the whole module?
- How can I export multiple things at once?
- Can I access variables and functions from a module if they were not exported?

Tips:

- Check the console. If you are having any syntax errors, you might get some hints there.
