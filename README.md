# School Hash Cracking Exercise

This small documentation is intended to help students practice identifying and understanding password hashes using common tools in a controlled, authorized educational setting.

## Provided hashes you'll have to crack:

### John the Ripper
`7d9410ac56be267a81a691ec5ccb4373`

### Hashcat
`2cf24dba5fb0a30e26e83b2ac5b9e29e1b161e5c1fa7425e73043362938b9824`

## Goal

The goal of this exercise is to understand:
- NO AI, find by working together
- how hashes are represented,
- why password security matters.
- How to crack passwords using common tools
- You have to research how John The Ripper and Hashcat works so that you can use it to find the passwords above

## Hash Identification with hashid

Before working with a hash, it is important to identify its type. The `hashid` tool can help guess the possible hash algorithm based on the hash string format and length.

### What hashid does
- Inspects a hash value
- Suggests possible hash types
- Helps narrow down which tool or mode may apply

## Tool selection

- **John the Ripper** is commonly used for many hash formats and password audit workflows.
- **Hashcat** is commonly used for GPU-accelerated password auditing and supports many hash modes.
- **hashid** helps identify the hash before choosing a tool.


## Important note

Always use these tools only in authorized educational, lab, or defensive security contexts.
