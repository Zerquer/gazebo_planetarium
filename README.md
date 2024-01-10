# Gazebo Planetarium Readme
### Description

Welcome to the Gazebo Planetarium! This repository contains models of various planets and an impressive building serving as a planetarium. The simulation can be launched using Gazebo to explore a fascinating virtual world.

![](/models/beispiel/materials/textures/Planetarium.png)

### Directory Structure

- **world:** This directory contains the Gazebo world for the planetarium. To start the simulation, open the terminal and enter the command `gazebo Planetarium`.

- **models:** This directory includes models of different planets and the planetarium building as 3D models. Images of the models are also available and can be imported in the same way as shown in the folder.

### Using Models

To use the models in your own Gazebo simulations, add the path to the models in your `.bashrc` file. Add the following command at the end of your `.bashrc` file:

```bash
export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:/Path/to/Your/Repository/gazebo_planetarium/models
```

Replace "/Path/to/Your/Repository" with the actual path to your Gazebo Planetarium repository.


### Custom Images

To integrate custom images as models in your own Gazebo simulation, follow these steps:

1. Create a new model or duplicate an existing one and rename it.

2. Create a folder named "material" and inside it, create subfolders "scripts" and "texture." Execute the following bash commands to create the folders:

```bash
mkdir material
cd material
mkdir scripts
mkdir texture
```

3. Adjust the model parameters as needed.

Result:

    MyCustomModel
        material
            scripts
            texture

