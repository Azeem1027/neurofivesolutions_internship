- **Core Mechanism**: **REST (Representational State Transfer)** is an architectural style that leverages the stateless **HTTP protocol** to enable communication between systems. Clients request resources using distinct **URIs**, and servers respond with data representations, typically in **JSON** format.
- **Key Takeaways**:
  * Operations are strictly mapping-bound to standard HTTP verbs: **GET**, **POST**, **PUT**, and **DELETE**.
  * Systems remain completely **stateless**; the server saves zero client context between separate requests.
- **Analogy**: Think of a digital restaurant menu. The menu items are **URIs**. You use standard actions like "bring me food" (**GET**) or "remove my plate" (**DELETE**). The chef fulfills the order without needing to know your life history.