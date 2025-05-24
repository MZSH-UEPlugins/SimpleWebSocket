# SimpleWebSocket Plugin

## 📖 Overview

**SimpleWebSocket** is a lightweight Unreal Engine plugin that enables seamless WebSocket communication directly from Blueprints. It is designed for developers who need real-time two-way data transfer between UE and external servers without writing C++.

---

## 🔧 Features

- 📡 Connect to any WebSocket server (ws:// only)
- 🔁 Multiple named WebSocket connections
- 🧠 Blueprint-accessible API for connect, send, and close
- 🧩 Message binding using Blueprint delegates
- 🚀 Optional auto-connect on project start
- 📦 Fully tested: works correctly in packaged builds

---

## 📝 Usage Notes

- ✅ **Packaging Support**: The plugin works as expected in packaged builds (Windows).
- ⚠️ **Connection Tip**: Do **not** use `localhost` as the server address. Always use `127.0.0.1` to avoid connection issues in packaged games.

---

## 📚 Documentation

Step-by-step usage instructions and blueprint examples are available in:  
[`./Docs/README.md`](./Docs/README.md)

---

## 📄 License Summary

This plugin is licensed for use in Unreal Engine projects, both personal and commercial.  
You may:

- ✔ Use this plugin in your own projects (commercial or non-commercial)  
- ✔ Modify the source code for internal use  

You may **not**:

- ❌ Redistribute, republish, or resell the plugin as-is or with modifications  
- ❌ Include the plugin in any software or asset bundle without written permission  

📄 Full license text is available in the [LICENSE](./LICENSE) file.

---

## ⚠️ Disclaimer

This plugin is provided “as is” with no guarantees. The author assumes no responsibility for any issues, bugs, or damages resulting from its use.  
Use at your own risk.

By using this plugin, you agree to the above license terms.

---

## 📮 Contact

For questions, support, or licensing inquiries, please contact:  
**mengzhishanghun@outlook.com**
