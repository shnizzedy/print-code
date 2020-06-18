# print-code

A small BASH wrapper to print a code file. Prints the file 2-sided on your default printer.

#### Usage

```bash
print-code /path/to/code_file
```

#### Under the hood

1. Uses `enscript` to create a postscript file at `/tmp/print_code.ps`
2. Prints `/tmp/print_code.ps` 2-sided on default printer
3. Deletes `/tmp/print_code.ps`

#### Reference
Tashian, Carl. “[Print out Your Code. On Paper](https://medium.com/@tashian/print-out-your-code-on-paper-7c760a376bca).” *Medium*, 2019 March 18.