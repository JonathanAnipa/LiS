# LiS

Title 

Lithium-Sulfur Battery Simulator (Go/JS)


Description

 A modular application tracking capacity degradation curves based on chemical reaction rates and the polysulfide shuttle effect.


Project Structure

```bash
LiS-simulator/
├── backend/
│   ├── main.go          # The entry point that starts the Go server
│   ├── simulator.go     # Your LiS battery math and logic lives here
│   └── server.go        # Handles sending data back and forth to JS
├── frontend/
        |--- templates/
│             ├── index.html       # The main webpage structure
        |--- static/
               |-─ styles.css       # (Optional) For making the UI look clean
│   ├── app.js           # The JS logic that draws graphs and grabs inputs
│        
|__ go.mod 
└── README.md            # Project documentation 
``` 