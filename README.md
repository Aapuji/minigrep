# MiniGrep
A mini version of the `grep` command, written in rust! It prints all the lines of the given file where the given text appears.

Following the tutorial in the [rust book](https://doc.rust-lang.org/book/ch12-00-an-io-project.html).

## Usage
After downloading, use:
```
cargo run -- <text> <filename>
```

This search is case sensitive, but you can use a case insensitive mode with the environment variable `IGNORE_CASE`:
```
$ IGNORE-CASE=1 cargo run -- <text> <filename>
```

Or with powershell: 
```
PS> $Env:IGNORE_CASE=1; cargo run -- <text> <filename>
```

## Default File
When downloading this, the `poem.txt` file will come with it so you can try it out without needing any other files. 
