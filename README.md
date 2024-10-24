# XLV (45) Editor

### XLV is a lightweigt minimal vim text editor written in Rust

#### Please note that this project is for learning purposes not to be assumed otherwise

##### Folder Structure
<code>
my-rust-editor/
│
├── src/
│   ├── editor/            # Core editor functionality
│   │   ├── mod.rs         # Editor module entry point
│   │   ├── buffer.rs      # Buffer management (for files)
│   │   ├── cursor.rs      # Cursor movement and positioning
│   │   ├── input.rs       # Input handling (keystrokes)
│   │   ├── renderer.rs    # Rendering text to terminal/screen
│   │   └── mode.rs        # Editor modes (normal, insert, visual)
│   ├── ui/                # UI components (optional)
│   │   ├── mod.rs         # UI module entry point
│   │   └── status_bar.rs  # Status bar display
│   ├── term/              # Terminal abstraction layer
│   │   ├── mod.rs         # Terminal module entry point
│   │   └── ansi.rs        # ANSI escape code handling for rendering
│   ├── config/            # Configuration and settings
│   │   ├── mod.rs         # Config module entry point
│   │   └── keymap.rs      # Key mappings for editor shortcuts
│   ├── main.rs            # Entry point of the program
│   └── lib.rs             # Library entry point (for structuring larger projects)
│
├── tests/                 # Unit and integration tests
├── Cargo.toml             # Rust dependencies and project metadata
└── README.md              # Project description
</code>
