# random_name
- This is a simple program for generating random names, allowing the user to specify
the placement of consonants and vowels.

## Running

```sh
cargo run
```

## Example Usage

```sh
# generating a random name with 2 consonants, a vowel, and one consonant
cargo run -- cvcv
# formating output, this will output h + " " + random consonant + random vovel
cargo run -- cvcv "h .."
```

