

This lesson introduces **Input/Output (I/O)** and **File Handling** in Python, which are essential for building practical programs.

All programs follow the pattern **input → processing → output**. Earlier programs used only `input()` and `print()`, but larger and more professional programs require better output formatting and the ability to read from and write to **files**.

Python provides several ways to **format output**:

* **F-strings** (modern and recommended): allow expressions inside `{}` and support powerful format specifiers.
* **`str.format()`**: an older but flexible method using replacement fields `{}`.
* **Manual formatting**: using methods like `ljust()`, `rjust()`, `center()`, and `zfill()`.
* **Old-style `%` formatting**: based on C-style formatting, now mostly outdated but still seen in older code.

Format specifiers allow control over **decimal precision**, **alignment**, **width**, **padding**, and **number representation** (binary, hexadecimal, etc.), making output neat and readable.

The lesson then explains **file handling**. Files can be treated as **text** or **binary**, and must be opened using the `open()` function before use. Files are opened in different **modes**, such as read (`r`), write (`w`), append (`a`), or read/write (`r+`).

Once opened:

* Files can be **read** using `read()`, `readline()`, `readlines()`, or by iterating over the file.
* Files can be **written** using `write()`, after converting non-string data to strings.
* The current position in a file can be checked with `tell()` and changed with `seek()`.

Because file operations may fail, **exception handling** is important. The recommended approach is using the **`with` statement**, which ensures files are automatically closed, even if an error occurs.

In summary:

* Python supports multiple ways to format output, with **f-strings** being the preferred method.
* File handling allows programs to store and retrieve data.
* Files must be opened before use and closed after use.
* The `with` statement provides a safe and clean way to work with files.


