## Instructions

### Main Window
In the main window, enter the number of vertices.

### Buttons

- **Enter**: Displays a table that allows you to input vertex data.
  ![Entering Data](images/entering_data.png)

- **Calculate**: Runs the function.

- **Table**: Displays a new window with the vertex data table.
  ![Vertex Table](images/vertex_table.png)

- **Chart**: Displays a new window with the Gantt chart.
  ![Gantt Chart](images/gantt_chart.png)

### Method of Entering Vertices into the Table

- **1st column** – Vertex name
- **2nd column** – Duration of the vertex
- **3rd column** – "Coefficient" - name of the predecessor

The coefficient must be a decimal number and separated from the vertex name by a hyphen (-). Predecessor names are separated by a semicolon (;).

### Example

| Vertex | Duration | Coefficient       |
|--------|----------|-------------------|
| A      | 30       | 0,5-B;C           |