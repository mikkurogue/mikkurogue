```rust
pub struct Mikku {
    pub name: &str,
    pub location: &str,
    pub languages: Vec<&str>,
    pub editor: &str,
    pub os: &str,
    pub periphs: (&str, &str),
};

impl Mikku {
    pub fn new() -> Self {
         Mikku {
            name: "Mikku",
            location: "Vantaa, Finland",
            languages: vec!["rs", "ts", "go"],
            editor: "Neovim",
            os: "Arch Linux",
            periphs: ("Corne 58 split keyboard", "MX Master 4s"),
        }
    }
}

```

Full stack programmer.
Finnish/Dutch

Mythic raider in WoW, I like games and anime alongside my programming.

Currently working on `srcvault`, a git forge alternative.



`Rust makes it hard to write bad code by making it hard to write code in general.`

