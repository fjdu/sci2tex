Convert a string representing a number in ``E-form'' to TeX form.

Example:

```
>> from sci2tex import sci2tex
>> print(sci2tex('12.340e+05'))
12.34{\times} 10^{5}
>> print(sci2tex('12.00e-05'))
12{\times} 10^{-5}
>> print(sci2tex('12.00'))
12
```
