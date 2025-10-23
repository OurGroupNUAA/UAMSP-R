Experimental Data and Results

This repository contains all the data and computational results required to replicate the experiments. The data and results are organized into two main folders, as described below:

Folder Structure

data: This folder contains all the generated random instance data. Each Excel file represents a specific problem scale, and the filename contains a description of that scale. For example, data_output_5_20.xlsx represents an instance with 5 machines and 20 parts.

Each Excel file contains multiple sheets, with each sheet representing a specific instance.

Each scale contains 10 different instances.

Each row in the sheet represents a specific task instance and contains the following fields:

Machines: The number of machines

Batches: The number of batches

Parts: The number of parts

Volume: The volume of parts

Height: The height of parts

Area: The area of the parts

Precision: The precision of parts

Release time: The release times of parts

Maximum height: The maximum height of the machines

Maximum area: The maximum area of machines

Maximum precision: The maximum precision of machines

Setup time: The setup time for machines

Time spent on per unit volume: Time spent on each unit volume of parts

Time spent on per unit height: Time spent on each unit height of parts

results: This folder contains the computational results for different solving methods, such as the original model, LBBD, symmetry-breaking constraints, and cuts.

Each solving method’s results are stored in a separate file for easy comparison with the data.

File Naming Conventions

For the Excel files in the data folder:

The files are named in the format data_output_<m>_<n>.xlsx, where m represents the number of machines and n represents the number of parts. For example, data_output_5_20.xlsx represents an instance with 5 machines and 20 parts.

Each Excel file contains multiple sheets, with each sheet representing an individual instance. There are 10 instances per scale.

For the files in the results folder:

The files are named according to the solving method used, for example:

OP_results.xlsx: Results of the original model

LBBD_results.xlsx: Results of the LBBD method

SBCs_constraints_results.xlsx: Results of using symmetry-breaking constraints

Cuts_results.xlsx: Results of using different cuts
