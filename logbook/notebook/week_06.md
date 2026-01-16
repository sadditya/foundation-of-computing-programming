

This lesson explains **Lists** and **Tuples**, which are important sequence data types in Python used to store multiple values together.

A **list** is an ordered and **mutable** sequence. This means elements can be added, removed, or changed after the list is created. Lists support indexing, slicing, iteration, and many built-in **methods** such as `append()`, `extend()`, `insert()`, `remove()`, `pop()`, `clear()`, `sort()`, and `reverse()`. Some methods modify the list (mutators), while others like `index()`, `count()`, and `copy()` only return values without changing the list.

Elements can also be removed using the **`del` statement**, which can delete single elements, slices, or even the entire list variable.

The lesson introduces **list comprehensions**, which provide a concise way to create lists programmatically. They use an expression combined with `for` loops and optional `if` conditions to generate list contents efficiently and clearly.

A **tuple** is another ordered sequence type, but unlike lists, tuples are **immutable**, meaning their contents cannot be changed once created. Tuples are often used to group a small number of related values, usually of different data types. They are created using commas (with or without parentheses).

Tuple elements are commonly accessed using **unpacking** (multiple assignment) or indexing. Tuples also support limited methods such as `count()` and `index()` that do not modify the tuple.

Tuples are widely used in **function arguments**, especially for variable-length argument lists (`*args`). Sequences can also be unpacked using `*` when calling functions.

In summary:

* Lists are mutable and usually store similar types of data.
* Tuples are immutable and usually store different types of data.
* List comprehensions provide a clean way to generate lists.
* Tuples support packing, unpacking, and flexible function argument handling.

