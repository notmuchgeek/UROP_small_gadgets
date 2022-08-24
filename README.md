# UROP_small_gadgets
Gadgets developed during my UROP intern

## Gadget 1: EXCEL Code to Readble code Converter
**File:** 'Readable Code Generator.ipynb'\
**How to use:** Use the function theFinalConverter(...str) ONLY\
**Examples:**\
**Input:**
```
# EXCEL CODE:
# '12gly25-21_5wt_7525'
# Readable code as the output
theFinalConverter('12gly25-21_5wt_7525')

# EXCEL CODE:
# '04-11_25wt_1000'
# Readable code as the output
theFinalConverter('04-11_25wt_1000')

# EXCEL CODE:
# '12-21DMSO_5wt_7525'
# Readable code as the output
theFinalConverter('12-21DMSO_5wt_7525')

# EXCEL CODE:
# '22(12)-21_7wt_7525'
# Readable code as the output
theFinalConverter('22(12)-21_7wt_7525')
```
\
**Output:**
```
Your input: 12gly25-21_5wt_7525
Readable code: C-112, L-Kraft, 5 wt.%, 75:25, Glycerol(25 wt.%);


Your input: 04-11_25wt_1000
Readable code: C-101, L-Kraft, 25 wt.%, 100:0;


Your input: 12-21DMSO_5wt_7525
Readable code: C-112, L-Kraft, 5 wt.%, 75:25, DMSO;


Your input: 22(12)-21_7wt_7525
Readable code: C-112, L-Kraft, 7 wt.%, 75:25;
```
