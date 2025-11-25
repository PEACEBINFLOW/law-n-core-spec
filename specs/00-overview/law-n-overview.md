# Law-N Overview

Law-N is a **network law layer** that treats the global network as a programmable organism.

Instead of:

> Computers talking over a neutral network using legacy protocols,

Law-N assumes:

> Signals, frequencies, towers, satellites, and routes are **first-class programmable objects.**

This doc covers:

- What’s broken in the current stack (CLFI – Current Layered Functional Internet)
- The core abstractions Law-N introduces
- Where LSIP, FBRP, GLCS, CLSI, N-SQL, and N-LLMs fit
- How this repo organizes the specs

## 1. CLFI in One Paragraph

CLFI is defined by:

- TCP/IP
- DNS
- HTTP(S)
- Application-level APIs
- Cloud as a “thing on top of the network”

It treats signals as a low-level detail and packets as the main object.

## 2. Law-N in One Paragraph

Law-N flips that:

- The **signal** is the primary object.
- Packets are just one representation.
- Towers, satellites, and routes are programmable.
- Cloud is **signal-native**, not just sitting on top of the network.

## 3. Main Components

- **LSIP** – how we define and verify signal identities  
- **FBRP** – how we route based on frequency & patterns  
- **GLCS** – how different G-layers are normalized  
- **CLSI** – the cloud interface that speaks in Law-N terms  
- **N-SQL** – how we query live network state  
- **N-LLMs** – models trained on signals and network patterns
