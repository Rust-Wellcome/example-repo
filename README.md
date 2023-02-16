# VCF Project – Example Repo

This is an example of how our repo might be structured. It has two crates:

- The `vcf` library crate: defines the concrete functionality of our project. This is used by our 
    CLI and may also be linked to by external crates.

- The `vcf-cli` binary crate: this would define the command-line executable for our project, which
    interprets the user's input and dispatches to our library crate accordingly.
