# minigrep

### Minigrep searches a specified file for a specified string. To do so, grep takes as its arguments a file path and a string. Then it reads the file, finds lines in that file that contain the string argument, and prints those lines.

## Built With 
- Rust

## Getting Started
- clone `https://github.com/Okechukwu-muokwugwo/minigrep.git`
- cd `minigrep`
- You can search for any word from `poem.txt` in root directory or created your file by typing `cargo run -- somebody poem.txt`

## Features
- `case sensitive` search
- `case insensitive` search

> Enable `case insensitive` search by setting the environment variable thus `$Env:IGNORE_CASE=1; cargo run -- To poem.txt`

