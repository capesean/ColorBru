# ColorBru
A .NET static class for the ColorBrewer lookup library developed by Cynthia Brewer

## Use
Use it by calling:
- `ColorBru.Palettes` to get a full list of the palettes;
- `ColorBru.GetColors(Code code, byte numberOfColors)` to get a list of `System.Drawing.Color` items for the given code & number;
- `GetHtmlCodes(Code code, byte numberOfColors)` same as above but returning a string array of Html color codes.

 
