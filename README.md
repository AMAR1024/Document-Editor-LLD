# 📝 Document Editor in C++ (OOP Design)

This is a simple **Document Editor system** built in **C++** using core Object-Oriented Design principles:

## 🚀 Features
- Add text elements
- Add images
- Add new lines and tab spaces
- Render full document
- Save document to file

## 🧠 Concepts Used
- Abstraction
- Inheritance
- Polymorphism
- Virtual functions & override
- Composition
- Separation of concerns

## 🏗 Architecture

- `DocumentElement` → Abstract base class
- `TextElement`, `ImageElement`, `NewLineElement`, `TabSpaceElement` → Derived classes
- `Document` → Holds elements
- `Persistence` → Storage abstraction
- `FileStorage` → Saves to file
- `DocumentEditor` → Client interface

## ▶️ How to Run

```bash
g++ DocumentEditor.cpp -o editor
./editor
