# Solid Waste Management System using SWEEP

SWEEP (Solid Waste Echelon Embedded Planner) is a web-based application for designing a Municipal Solid Waste (MSW) management system. Through SWEEP, a user can choose locations for each node in an echelon, input the land and size configuration cost of facility/container, and generate a MSW management system based on the input values. The resulting MSW management system is obtained by solving a “Multi-Echelon Location Routing problem” using Gurobi, which yields the optimal configuration of the MSW management system.



For installation of libraries just type "pip install -r requirements.txt" in the terminal under sweep_backend
To run the flask server, use the command "python app.py"

For launching the tool: 
1. Under the vite-project directory run "npm run dev" (check for "npm" installation under vite-project). This would provide a URL to launch the application
2. Under sweep_backend directory, run "python app.py" for using gurobi.

After launching the tool, you can follow instructions under the guideline page, for how to use the application for desigining a MSW management system.
