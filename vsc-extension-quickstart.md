# Starters - VS Code Snippets Extension

Quickly generate starter files and boilerplate code for projects in multiple programming languages including C++, JavaScript, PHP, Python, Go, Rust, Ruby, and Java.

With this extension, users can **simply download it from the VS Code Marketplace** and start using the snippets in their own projects or files—no extra setup required.

---

## What's in the folder

* `package.json` – Defines the extension metadata and snippet file locations for each language.
* `snippets/` – Contains all the snippet JSON files organized by language:
  * `cpp/base.json` & `cpp/oop.json`
  * `javascript/base.json`, `javascript/express.json`, `javascript/web.json`, `javascript/react.json`
  * `php/base.json`, `php/laravel.json`
  * `python/base.json`, `python/flask.json`, `python/django.json`
  * `go/base.json`, `go/web.json`
  * `rust/base.json`, `rust/web.json`
  * `ruby/base.json`, `ruby/rails.json`
  * `java/base.json`, `java/oop.json`, `java/web.json`

---

## How to use

1. Download and install the extension from the VS Code Marketplace.  
2. Open or create a file in your desired language (e.g., `.java`, `.js`, `.py`).  
3. Start typing the snippet **prefix** (like `java-base`, `js-base`, etc.).  
4. Select the snippet from IntelliSense suggestions and press **Tab** or **Enter** to insert it.  

> ✅ Users can immediately use the snippets in any project file—no additional configuration needed.

---

## Make changes (for developers)

* Edit any snippet JSON file in the `snippets/` folder.  
* Relaunch the extension via the debug toolbar or reload the window (`Ctrl+R` or `Cmd+R` on Mac) to see changes.  

---

## Install your extension locally (optional)

* Package your extension with:

```bash
vsce package
