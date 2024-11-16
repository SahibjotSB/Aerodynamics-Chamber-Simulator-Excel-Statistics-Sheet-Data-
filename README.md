
### README for Physics Simulation with Pymunk

#### Project Overview
This project demonstrates a physics simulation built using Pygame, Pymunk, and Matplotlib, featuring dynamic circles and static shapes under the influence of physics. It also includes functionality for saving simulation data to an Excel file and generating visualizations.

---

#### Features
- Dynamic simulation with gravity and aerodynamics.
- Interactive addition of circles via mouse clicks.
- Average speed calculation for dynamic objects.
- Static shapes (box, circle, polygon) included in the environment.
- Data collection and export to an Excel file with an embedded speed graph.
- Graphical display of simulation metrics using Matplotlib.
- Responsive UI powered by Pygame.

---

#### Setup Instructions
1. Install Python (3.9 or above)  
   Download Python from https://www.python.org/downloads/.

2. Install Required Libraries  
   Run the following command to install dependencies:
   ```bash
   pip install pygame pymunk openpyxl matplotlib yagmail
   ```

3. Add Required Assets
   - Ensure the file `blue-glossy-ball-png.webp` is in the same directory as the script.

4. Run the Program
   Run the script using the command:
   ```bash
   python script_name.py
   ```

---

#### Controls
- Mouse Click: Add a new dynamic circle at the cursor's position.
- Window Close: Exit the simulation, save data to Excel, and close the application.

---

#### Output
1. Graphical Simulation: 
   - Dynamic circles and static shapes interact on the screen.
   - Average speed of circles is displayed at the top.

2. Excel File: 
   - Data (time and average speed) is saved to `simulation_data.xlsx`.
   - A graph showing speed trends is embedded in the Excel file.

---

#### Modules Used
- Pygame: For rendering and interaction.
- Pymunk: For physics simulation.
- OpenPyXL: For Excel file generation and graph embedding.
- Matplotlib: For graph plotting.
- Yagmail: Optional email functionality for sending results (can be implemented if required).

---

#### Customization
- Gravity: Modify the line `space.gravity = (500, 0)` to change the gravity vector.
- Data Collection Interval: Change `data_collection_interval` to adjust how frequently data is recorded.
- Static Shapes: Modify `create_shape()` calls in the `main()` function to customize the environment.

---

#### Future Enhancements
- Add more interaction options, such as keyboard controls or additional shapes.
- Include email functionality to send simulation results automatically.
- Extend the simulation to 3D using libraries like PyOpenGL.

---

#### Acknowledgments
This project leverages powerful Python libraries to create an engaging and educational simulation environment.
