# Deletion Commands (normal mode)

## Basic Deletion Commands 

1. **Delete a Character:**

- `x`: Deletes the character under the cursor.
- `X`: Deletes the character before the cursor.

2. **Delete the Current Line:**

- `dd`: Deletes the entire current line.

3. **Delete Until the End of the Line**:

- `D (or d$)`: Deletes from the cursor to the end of the line.

4. **Delete Until the Beginning of the Line**:

- `d0`: Deletes from the cursor to the beginning of the line.

## Deleting Words

1. **Delete the Current Word:**

 - `dw`: Deletes from the cursor to the end of the current word.

2. **Delete the Current Word Backwards:**

- `db`: Deletes from the cursor to the beginning of the current word.

3. **Delete the Entire Word Under the Cursor:**

- `daw` (delete a word): Deletes the whole word, including any trailing whitespace.

4. **Delete the Inner Word:**

- `diw` (delete inner word): Deletes the word under the cursor without trailing whitespace.

## Deleting Blocks of Text

1. **Delete a Paragraph:**

- `dap`: Deletes the paragraph under the cursor, including trailing whitespace.

- `dip`: Deletes the inner paragraph (no trailing whitespace).

2. **Delete Between Parentheses/Braces/Quotes:**

- `di( or di)`: Deletes inside parentheses.

- `di{ or di}`: Deletes inside curly braces.

- `di' or di"`: Deletes inside quotes.

- Use `da` instead of `di` to include the surrounding characters (e.g., `da`( deletes the parentheses as well).

## Deleting with Ranges

1. **Delete a Specific Number of Lines:**

- `d<N>j`: Deletes the current line and the next <N> lines (e.g., d5j deletes 6 lines total).
- `d<N>k`: Deletes the current line and the previous <N> lines.

2. **Delete From the Current Line to Another Line:**

- `dG`: Deletes from the current line to the end of the file.

- `dgg`: Deletes from the current line to the beginning of the file.

`:10,20d`: Deletes lines 10 through 20.

## Combining with Motions

Vim's deletion commands can be combined with motion commands to delete custom ranges:

1. **d + Motion Command:**

- `d$`: Delete to the end of the line.

- `d^`: Delete to the first non-whitespace character of the line.

- `d/word`: Delete to the next occurrence of "word."

## Undo Deletion

- If you delete something by mistake, press u in normal mode to undo the last change.

  *This content was made using chat-GPT.*
