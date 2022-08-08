# Taichia-Chialisp

The chialisp programs of Taichia services

- core - Puzzles are widely used in multiple services
- donation - Puzzles for donation service only
- libs - Chia original libs
- payroll - Puzzles for payroll service only
- vote - Puzzles for vote service only


## How to verify
There are two ways to prove we are using puzzles in this repository.

### A. Compare the puzzles
You can decompile all these puzzle from any full-node and compare with the puzzles in this repository. If they are match then you know we are using these puzzles.

### B. Compare the puzzle hash
You can curry your parameters into the puzzles we provided. The puzzle hash of the curried puzzle should equal to what you saw on the Chia explorers.
Since you may not curry parameter in a way as we did, you may see a mismatch of puzzle hash. If you have any concern just go to our Discord server (https://discord.gg/jSxR7DBcjW) and ask our developers.


