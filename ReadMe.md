# Environment Variables in bash :sunflower:

This class is on Environment variables.

### What is a variable?

A variable is like a box, you can put thing inside and extract from it.

For us an environment is a system where code runs for different purposes. Usually at least 3 environments exists:
- Dev
- Testing
- Productions

**Environment variables** are variables that exist on said environments and are interpolated from the environments AND NOT from the code.

**environments variables exist in the machine NOT the code.**

This is great for things:
- Risk Reduction
- things that you don't want to have in your code!
- like **access keys**
- AWS_SCRETE keys

```bash

MY_VAR = GOODYEAR
MYVAR #Command not found
echo MY_VAR #returns MY_VAR
echo $MY_VAR #returns GOODYEAR

MY_VAR=$(pwd)
echo MY_VAR #returns pwd now 

```
