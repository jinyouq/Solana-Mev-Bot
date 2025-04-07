How to download rust:
    1. vi ~/.zshrc
    2. 
        export RUSTUP_DIST_SERVER=https://mirrors.tuna.tsinghua.edu.cn/rustup
        export RUSTUP_UPDATE_ROOT=https://mirrors.tuna.tsinghua.edu.cn/rustup/rustup
    3. curl https://sh.rustup.rs -sSf | sh
    4. mkdir -p ~/.cargo 
    5. vi ~/.cargo.config
    6. 
        [source.crates-io]
        replace-with = 'tuna'
        
        [source.tuna]
        registry = "https://mirrors.tuna.tsinghua.edu.cn/git/crates.io-index.git"
        
How to download solana:
    1. https://github.com/solana-labs/solana/releases/tag/v1.14.17
    2. Download release package
    3. 
        export PATH="$HOME/solana/solana-release/bin:$PATH"
        
