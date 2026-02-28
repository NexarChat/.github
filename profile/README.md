# Nexar Chat

**Nexar Chat** is a hybrid communication platform designed to support both centralized and decentralized deployment models.

Our goal is to provide a modern, self-hostable, secure, and modular alternative to traditional communication platforms — while giving users full control over their infrastructure.

---

## Vision

Nexar Chat is built around a **hybrid architecture**:

* **Centralized Mode**
  A hosted main instance managed by the core project.

* **Decentralized Mode**
  Fully self-hosted private instances, completely isolated and independently operated.

This allows individuals, communities, and organizations to choose their preferred deployment model without vendor lock-in.

---

## Repository Structure

The organization is structured into separate repositories:

* **Server** – Backend implementation (API, auth, realtime, persistence)
* **Client** – Frontend application
* **Core** – Integration repository (uses Git submodules to reference Server and Client)
* **.github** – Organization-wide configuration (this repository)

---

## Technology Stack

* **Language:** TypeScript
* **Runtime:** Node.js (Server)
* **Client:** Web-based (framework TBD)
* **Architecture:** Modular, extensible, deployment-agnostic

---

## Contributing

We aim to maintain:

* Clean, typed, maintainable code
* Strict separation of concerns
* Clear architectural boundaries between modules
* Self-hosting as a first-class feature

Contribution guidelines and templates are defined in this repository.

---

## Philosophy

* No forced central authority
* No mandatory public exposure
* Full infrastructure ownership
* Clean, scalable system design