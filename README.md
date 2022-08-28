# PowerAutomate
The purpose of this repo is to store the JSON files for useful Power Automate and Logic Apps automations

## Usefull Expressions
A list is included below with useful Workflow Definition Language Expressions

### Working with strings

#### Text after a delimiter

Expression: `@slice(variables('txt2'), add(lastIndexOf(variables('txt2'), ' '), 1))`

How to use
- Replace `variables('txt2')` with your text or variable
- Replace the delimiter `' '` with your delimiter.


