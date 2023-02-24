# Navigation development

This is a test project used for developing the navigation system for both robots (tiramisu and croissant) independently of other modules.

## Setup

To get started, create an env.mk file and specify host and user just like normal. Additionaly add a compiler flag to define whether to comile for croissant or tiramisu:

```ini
# deployment host config
USER = access
HOST = 10.42.0.149
CARG = -D__CROISSANT  # for croissant development
CART = -D__TIRAMISU   # for tiramisu development
```
