# Starters - VS Code Snippets Extension

Quickly generate starter files and boilerplate code for projects in multiple programming languages including C++, JavaScript, PHP, Python, Go, Rust, Ruby, Java, and Hono.

With this extension, users can **simply download it from the VS Code Marketplace** and start using the snippets in their own projects or files—no extra setup required.

---

## Features

* Ready-to-use code snippets for multiple programming languages
* Organized by language for easy access
* Helps developers save time writing boilerplate code
* Works in any project file immediately

> Tip: You can showcase this extension by adding screenshots or GIFs in an `images/` folder.

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
  * `hono/base.json`, `hono/web.json`

---

## Snippet Cheat Sheet

| Language   | Snippet Prefix  | Description                       |
|------------|-----------------|-----------------------------------|
| C++        | `cpp-base`      | Basic C++ file boilerplate        |
| C++        | `cpp-oops`      | Simple C++ class & object         |
| JavaScript | `js-base`       | Basic JS function                 |
| JavaScript | `js-express`    | Express.js route setup            |
| JavaScript | `js-web`        | Basic HTML + JS web setup         |
| JavaScript | `js-react`      | React component boilerplate       |
| PHP        | `php-base`      | Basic PHP file                    |
| PHP        | `php-laravel`   | Laravel controller example        |
| Python     | `py-base`       | Basic Python file                 |
| Python     | `py-flask`      | Flask route setup                 |
| Python     | `py-django`     | Django view example               |
| Go         | `go-base`       | Basic Go file                     |
| Go         | `go-web`        | Go HTTP server boilerplate        |
| Rust       | `rust-base`     | Basic Rust file                   |
| Rust       | `rust-web`      | Rust web server example           |
| Ruby       | `ruby-base`     | Basic Ruby file                   |
| Ruby       | `ruby-rails`    | Rails controller example          |
| Java       | `java-base`     | Basic Java class                  |
| Java       | `java-oops`     | Java class & object example       |
| Java       | `java-web`      | Java servlet/endpoint setup       |
| Hono       | `hono-base`     | Minimal Hono starter app          |
| Hono       | `hono-web`      | Hono app with GET & POST routes   |

---

## How to use

1. Download and install the extension from the VS Code Marketplace.  
2. Open or create a file in your desired language (e.g., `.java`, `.js`, `.py`, `.ts`).  
3. Start typing the snippet **prefix** (like `java-base`, `js-base`, `hono-base`).  
4. Select the snippet from IntelliSense suggestions and press **Tab** or **Enter** to insert it.  

> ✅ Users can immediately use the snippets in any project/file—no additional configuration needed.

---

## Make changes (for developers)

* Edit any snippet JSON file in the `snippets/` folder.  
* Relaunch the extension via the debug toolbar or reload the window (`Ctrl+R` or `Cmd+R` on Mac) to see changes.

---

## Install your extension locally (optional)

* Package your extension with:

```bash
vsce package
