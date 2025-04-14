### Doubly Linked List (Subway Simulation)

[![Made with Node.js](https://img.shields.io/badge/Made%20with-Node.js-brightgreen?logo=node.js)](https://nodejs.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This project implements a **Doubly Linked List** in Node.js to simulate a subway system. You can add stations to the front or back, remove them, and print the current route.

---

### Project Structure

|Node.cjs               # Node class (each station)
| DoublyLinkedList.cjs   # Core doubly linked list logic
|index.js               # Script to simulate and test the subway line

---

## How to Run

 Clone the Repo
go to bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
node index.js

 ### Features
	•	 addToHead(data) – Add a station to the front
	•	 addToTail(data) – Add a station to the end
	•	 removeHead() – Remove the first station
	•	 removeTail() – Remove the last station
	•	 removeByData(data) – Remove a station by name
	•	 printList() – Print all stations in order

### Example Outfit
<head> CentralPark GrandCentral TimesSquare <tail>
<head> CentralPark GrandCentral TimesSquare PennStation WallStreet BrooklynBridge <tail>
<head> GrandCentral TimesSquare PennStation WallStreet <tail>













