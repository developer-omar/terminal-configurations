# My Zellij Configuration

1. Install [Zellij](https://zellij.dev/documentation/installation) according
to your operating system,I installed this with
Rust-Cargo with the following commands:

    ```bash
    #install rustup, rust and cargo
    curl https://sh.rustup.rs -sSf | sh
    ```

    ```bash
    cargo install --locked zellij
    ```

2. (Optional) Place the following code at the end of the file ~/.zshrc
or ~/.bashrc to [integrate zellij in your terminal](https://zellij.dev/documentation/integration)

    ```bash
    echo 'eval "$(zellij setup --generate-auto-start bash)"' >> ~/.bashrc
    ```

    ```bash
    echo 'eval "$(zellij setup --generate-auto-start zsh)"' >> ~/.zshrc
    ```
