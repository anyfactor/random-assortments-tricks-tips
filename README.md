# random-assortments-tricks-tips
General stuff I found whether I keep forgetting about it or it was just interesting

## Python

### Dual digit date system.

``datetime`` module outputs date information in ``int`` type, so there is the "0" at the beginning missing. So solution -

```python
'{:02d}'.format(now.1)
> '01'
'{:02d}'.format(now.11)
. '11'
```
