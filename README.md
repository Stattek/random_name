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

# formatting output, this will output 'h' followed by a space, then the next two random characters in the generated random name.
cargo run -- cvcv "h .."
```
