IPC Visualization Tool

An interactive web-based tool designed to visually demonstrate how different Inter-Process Communication (IPC) mechanisms work between processes. This project helps students, beginners, and OS learners understand how data is transferred using techniques such as Named Pipes, Message Queues, and Shared Memory.

This visualization uses HTML5 Canvas animations and JavaScript logic to simulate real-time message passing between processes in a simple and intuitive interface.

🚀 Features

Visual simulation of three IPC mechanisms:

Named Pipe

Message Queue

Shared Memory

Smooth animation of data packets traveling between processes.

User-controlled:

Source and target process selection

Message input

IPC type switching

Start, Stop, and Reset actions

Real-time event log displaying message send/receive events.

Clean, modern UI with gradient background and responsive controls.

Canvas-based drawing for processes, connections, and data packets.

🛠️ Tech Stack

HTML5 – Structure and Canvas element for visualization

CSS3 – Gradients, UI styling, animations, layout formatting

JavaScript (Vanilla JS) – Core logic for:

Drawing processes and connections

Animating packet movement

Managing IPC types

Logging events

Handling user interactions

Files used in the project:

index.html – App layout and UI controls 

index

script.js – Simulation logic, animation, IPC behavior 

script

styles.css – Modern styling and visual enhancements 

styles

📂 Project Structure
📁 ipc-visualization-tool
│
├── index.html
├── styles.css
└── script.js

▶️ How to Run the Project

Download or clone the repository:

git clone https://github.com/your-username/ipc-visualization-tool.git


Open index.html in any modern browser:

Chrome

Edge

Firefox

Start the simulation by:

Selecting IPC type

Choosing source & target process

Entering a message

Clicking Send Message

No installation or backend setup required.

📸 Screenshots

(Add images here after pushing to GitHub)

/screenshots/home.png  
/screenshots/pipe.png  
/screenshots/message-queue.png  
/screenshots/shared-memory.png

📘 Use Cases

Operating Systems academic projects

Lab assignments for IPC mechanisms

Teaching tool for OS communication concepts

Visualization for distributed systems basics

📌 Future Enhancements

Add more IPC mechanisms (Sockets, Semaphores)

Multi-process simulation (more than 2 processes)

Different message packet shapes/speeds

Dark mode UI

Step-by-step mode for teaching

👨‍💻 Author

Munnaluri Maadhava
B.Tech CSE
Lovely Professional University

📄 License

This project is open-source and available under the MIT License.
