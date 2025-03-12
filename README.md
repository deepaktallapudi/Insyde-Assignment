# Insyde-Assignment

# AI Furniture Layout Generator


It generates synthetic room layouts by randomly placing furniture items in a 10x10 grid. The goal is to create structured room layouts while ensuring optimal space utilization. Each layout receives a heuristic score to evaluate its efficiency.

Steps to Use

# Step 1: Install Dependencies

Ensure you have the necessary Python libraries installed:

pip install numpy

#  Step 2: Open the Notebook

Run the following command to open the Jupyter Notebook:

jupyter notebook Insyde(Main).ipynb

# Step 3: Understand the Structure

The notebook defines a room size of 10x10.

It includes predefined furniture options with specific dimensions.

It ensures non-overlapping placement of furniture in the grid.

A heuristic score is assigned to evaluate layout efficiency.

The generated data is saved as a JSON file (synthetic_data.json).

# Step 4: Execute the Notebook

Run the cells in order to:

Define room dimensions and furniture types.

Generate random furniture placements while ensuring valid positioning.

Compute a heuristic score for each layout.

Save the generated dataset as synthetic_data.json.

# Step 5: Output Details

After execution, the generated dataset will be stored in:

synthetic_data.json

This file contains a list of generated layouts, each with its respective score.

# Step 6: Customization Options

Modify ROOM_WIDTH and ROOM_HEIGHT to change the room size.

Update the FURNITURE dictionary to add or remove furniture types.

Adjust the scoring heuristic as needed for different use cases.

# Step 7: License

This project is open-source and can be modified as needed.
