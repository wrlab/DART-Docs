# Installation

This page describes installation for the compute node (server + viewer).

=== "Docker (recommended)"
    ```bash
    git clone https://github.com/wrlab/DART.git
    cd <YOUR_REPO>
    docker compose up --build
    ```

=== "Native"
    ```bash
    git clone https://github.com/wrlab/DART.git
    cd DART
    python -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    ```

!!! note "Replace template commands"
    Update this page with your actual scripts and required versions once finalized.
