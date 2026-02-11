## 🧠 OpenPayments

**OpenPayments** is a lightweight, open-source Go library designed to make working with multiple payment providers simple and predictable.

In real-world applications, relying on just one payment gateway is often not enough. You may need redundancy, better regional coverage, cost optimization, or the flexibility to switch providers as your business grows. The challenge? Every provider has its own API style, request format, response structure, and error handling model. Managing them individually quickly turns into duplicated logic, messy conditionals, and tight vendor lock-in.

OpenPayments removes that complexity.

It gives you:

- A single, clean interface for charging and refunding payments  
- A provider-agnostic request and response model  
- Consistent, normalized error handling across gateways  
- Deterministic routing strategies like priority and failover  
- Strict wrapping of official SDKs — no custom HTTP reimplementation  

OpenPayments does **not** process payments.  
It does **not** store transactions.  
It does **not** act as a gateway.  

It simply helps you integrate multiple payment providers in a clean, reliable, and maintainable way — so you can focus on building your product, not managing payment complexity.
