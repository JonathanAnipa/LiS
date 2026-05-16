# LiS

Project Structure

LiS-simulator/
├── backend/
│   ├── go.mod
|   ├── main.go          # The entry point that starts the Go server
│   ├── simulator.go     # Your LiS battery math and logic lives here
│   └── server.go        # Handles sending data back and forth to JS
├── frontend/
│   ├── index.html       # The main webpage structure
│   ├── app.js           # The JS logic that draws graphs and grabs inputs
│   └── styles.css       # (Optional) For making the UI look clean
└── README.md            # Project documentation 