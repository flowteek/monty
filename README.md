# Monty

`Monty 0.98` is a scripting language that is first compiled into monty byte codes (Just like python). It relies on a unique stack, with specific instructions to manipulate it. **`monty`** is an interpreter built specially for the said Monty Bytecodes files.

`monty` executes the following opcodes:

| Opcode | Description |
| -------- | ----------- |
| `push` | Pushes an element to the stack |
| `pall` | Prints all the values on the stack |
| `pint` | Prints the value at the top of the stack |
| `pop` | Removes the top element of the stack |
| `swap` | Swaps the top two elements of the stack |
| `queue` | Sets the format of the data to a queue (FIFO) |
| `stack` | Sets the format of the data to a stack (LIFO) |
| `nop` | Doesn't do anything |
| `add` | Adds the top two elements of the stack |
| `sub` | Subtracts the top element of the stack from the second top element of the stack |
| `mul` | Multiplies the second top element of the stack with the top element of the stack |
| `div` | Divides the second top element of the stack by the top element of the stack |
| `mod` | Computes the rest of the division of the second top element of the stack by the top element of the stack |
| `pchar` | Prints the char at the top of the stack |
| `pstr` | Prints the string starting at the top of the stack |
| `rotl` | Rotates the stack to the top |
| `rotr` | Rotates the stack to the bottom |

Comments, indicated with `#`, are not executed by the interpreter.

## Authors
<details>
    <summary>Ogunbanjo Samuel</summary>
    <ul>
    <li><a href="https://www.github.com/flowteek">Github</a></li>
    <li><a href="mailto:samuelogunbanjo@gmail.com">e-mail</a></li>
    </ul>
</details>
