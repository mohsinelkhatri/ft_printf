<h1 align="center" style="color:#4CAF50; text-align:center;">✨ ft_printf – Custom Printf Implementation ✨</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Project-42%20/%201337%20School-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Mandatory%20Only-green?style=for-the-badge">
</p>

<p style="font-size: 18px;">
<b>ft_printf</b> is a full reimplementation of the standard <code>printf</code> function in C.  
This project teaches formatted output, variadic arguments, and low-level data formatting.  
<br>🔥 <b>Bonus part not included</b>, as requested.
</p>

<hr>

<h2 align="center" style="color:#FF9800; text-align:center;">🚀 Features (Mandatory Part)</h2>

<p>The following conversions are implemented:</p>

<table style="border-collapse: collapse; width: 100%;">
<tr style="background-color:#ececec;">
  <th style="padding: 8px; border:1px solid #ccc;">Conversion</th>
  <th style="padding: 8px; border:1px solid #ccc;">Description</th>
</tr>

<tr><td style="padding: 8px; border:1px solid #ccc;">%c</td><td style="padding: 8px; border:1px solid #ccc;">Print a character</td></tr>
<tr><td style="padding: 8px; border:1px solid #ccc;">%s</td><td style="padding: 8px; border:1px solid #ccc;">Print a string</td></tr>
<tr><td style="padding: 8px; border:1px solid #ccc;">%p</td><td style="padding: 8px; border:1px solid #ccc;">Print a memory address</td></tr>
<tr><td style="padding: 8px; border:1px solid #ccc;">%d / %i</td><td style="padding: 8px; border:1px solid #ccc;">Print signed integers</td></tr>
<tr><td style="padding: 8px; border:1px solid #ccc;">%u</td><td style="padding: 8px; border:1px solid #ccc;">Print unsigned integer</td></tr>
<tr><td style="padding: 8px; border:1px solid #ccc;">%x / %X</td><td style="padding: 8px; border:1px solid #ccc;">Print hexadecimal (lowercase/uppercase)</td></tr>
<tr><td style="padding: 8px; border:1px solid #ccc;">%%</td><td style="padding: 8px; border:1px solid #ccc;">Print a percent sign</td></tr>
</table>

<hr>

<h2 align="center" style="color:#2196F3; text-align:center;">📁 Project Structure</h2>

<pre style="background:#1e1e1e; color:#00e676; padding:15px; border-radius:8px;">
ft_printf/
│
├── ft_printf.c        // main function logic
├── ft_printf.h        // header
├── ft_printf_utils.c  // helpers (hex, digits, strings)
├── Makefile
└── additional utils depending on your code
</pre>

<hr>

<h2 align="center" style="color:#9C27B0; text-align:center;">🛠️ Compilation</h2>

<pre style="background:#1e1e1e; color:#fff; padding:15px; border-radius:8px;">
make          # compile library
make clean    # remove object files
make fclean   # remove all + library
make re       # rebuild fully
</pre>

Resulting library:

<pre style="background:#1e1e1e; color:#4FC3F7; padding:15px; border-radius:8px;">
libftprintf.a
</pre>

<hr>

<h2 align="center" style="color:#E91E63; text-align:center;">💡 Usage Example</h2>

<pre style="background:#212121; color:#fff; padding:15px; border-radius:8px;">
#include "ft_printf.h"

int main(void)
{
    int count = ft_printf("Hello %s!\\n", "world");
    ft_printf("Printed %d characters.\\n", count);
    return 0;
}
</pre>

Compile with:

<pre style="background:#1e1e1e; color:#fff; padding:15px; border-radius:8px;">
cc main.c libftprintf.a
</pre>

<hr>

<h2 align="center" style="color:#3F51B5; text-align:center;">🧪 Testing</h2>

<ul>
  <li>🔥 printfTester (Tripouille)</li>
  <li>pft</li>
  <li>libft-war-machine</li>
</ul>

<hr>

<h2 align="center" style="color:#009688; text-align:center;">📚 Learning Outcomes</h2>

<ul>
  <li>Understanding how <b>printf</b> works internally</li>
  <li>Variadic functions (<code>va_list</code>)</li>
  <li>Hexadecimal & decimal conversions</li>
  <li>Pointer formatting</li>
  <li>Clean modular C architecture</li>
</ul>

<hr>

<h2 align="center" style="color:#795548; text-align:center;">📜 License</h2>

<p style="font-size:16px;">
This project is part of the <b>42 Network / 1337 School</b> curriculum.  
</p>

<hr>

<h1 align="center" style="color:#4CAF50; text-align:center;">🌟 Happy Coding! 🌟</h1>
