
key learnings:-
* **The Call Stack:** The LIFO (Last-In-First-Out) structure where the actual execution happens.
* **Web APIs:** Offloading long-running tasks (Timers, Fetches) to the browser environment.
* **Task Prioritization:** 1. **Microtask Queue:** VIP lane for Promises (`.then`).
    2. **Callback Queue:** Standard lane for `setTimeout`.
* **The Event Loop:** The mechanism that monitors the stack and pushes tasks when the engine is idle.
