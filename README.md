# Power Automate & Logic Apps
The purpose of this repo is to store useful Power Automate and Logic Apps workflows and expressions

## Useful Expressions
A list is included below with useful Workflow Definition Language Expressions

Functions Reference from Microsoft: [Click here](https://docs.microsoft.com/en-us/azure/logic-apps/workflow-definition-language-functions-reference) 

### Working with strings

#### Text after a delimiter

Expression: `@slice(variables('txt2'), add(lastIndexOf(variables('txt2'), ' '), 1))`

How to use
- Replace `variables('txt2')` with your text or variable
- Replace the delimiter `' '` with your delimiter.


