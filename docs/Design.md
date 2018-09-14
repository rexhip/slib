## Design principles

- Variable names should be expressive enough to be intuitive indicate the function. Well know discipline abbreviation may be used, but no home made once.

- Featers should always be balanced against resource requirement, and complexity increase of the code.

- Backward compatibility should be keeped.

- Code should be well commented.

- There are limits on the stack, for instance on a interrupt for S7-1200 the stack is only six layer deep. For this reason function nesting should be keeped at as few layer as possible.

### Code specific guidelines

- On larger functions blocks, input should be prefixed with «i», outputs should be prefixed with «q», static internal variables should be prefixed with «s» and temperary variables should be prefixed with «t». This guideline doesn't need to be enforced on samler function blocks.

- Constants should be in uppercase letters.

- Code should be written as simple as possible.

- Immutability: Varaibles should be not overwritten when they have benn set to a value. 

