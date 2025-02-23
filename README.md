# 📝 Rust CLI To-Do List  

A simple command-line to-do list application written in Rust. This project is designed to practice Rust fundamentals, including **structs, enums, file I/O, error handling, command-line arguments, and serialization (Serde).**  

## 🚀 Features  

- Add, remove, and list tasks 📋  
- Mark tasks as completed ✅  
- Task prioritization 🔥  
- Persistent storage using JSON or TOML 🗄️  
- Interactive CLI experience (optional)  

## 📦 Installation  

Ensure you have Rust installed:  

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## 🚀 Getting Started  
```bash
git clone https://github.com/Tobias-Johannesson/rust-cli-todo.git
cd rust-cli-todo
cargo run -- --help
```

## 📌 Usage
Add a new task
```bash
cargo run -- add "Write Rust blog post"
```

List tasks
```bash
cargo run -- list
```

Mark task as completed
```bash
cargo run -- complete 1
```

Remove a task
```bash
cargo run -- remove 1
```


