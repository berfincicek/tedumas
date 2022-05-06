# TEDU Multi Agent Systems, aka tedumas
A multiagnet system simulation for my senior project

### How to run?
- Start the server from the massim_2022 repository (https://github.com/berfincicek/massim_2022)
- Run the main class on this repository
- For editing the "main"s configurations, use "--add-opens=java.base/java.io=ALL-UNNAMED" for VM options
- Need to manually add "perst" library from the libs folder to the project structure
- Can see the map and agents from localhost:8000
- Can examine the written percepts from the "logs" folder, it produces a new txt file every run and updates it with every percept encountered 

### Known Bugs
- Even though the default assigned role to the agents have ability to attach a block, still failed_role is encountered. 
