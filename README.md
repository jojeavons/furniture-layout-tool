# furniture-layout-tool
A project to help visualize possible furniture layouts in a 2D space. 
# README

# Project Overview 

This project is a simple tool designed to allow users to plan furniture layouts of rooms in their house. My wife and I often like to rearrange whole rooms in our house, and we've learned over the years that planning things out on a grid is much easier than just trying to move things and hoping it works.

This will hopefully make things easier than using craft paper and scissors. 

## Technical Specs 

As a User, I can:

### Room
* Configure a basic rectangular 2D "room" that is a grid 
* Pull furniture items from a library of furniture definitions to add to the room
* View placed furniture items displayed on the grid of the room, color-coded by type
* Hover my mouse over a piece of furniture and view a tooltip that displays the furniture piece's info
* Adjust the scale of the room's grid, adjusting between the 1ft and 5ft 

### Furniture
* Pull furniture pieces from a pre-defined default library 
* Search for a piece of furniture from the library by name
* Add new custom pieces of furniture to the library
* For each piece of furniture I add, I can denote
  * length
  * width
  * name
  * notes 
  * type (seat, table, decoration, other)

### Interface 
* Download my current room configuration as a JSON file to use again later
* Upload a JSON file to import a room state and continue working

# Technical Details 

## Ruby Version

## Local Development

### Database Creation

### Database Initialization

### Running Test Suites 

### Running Locally

## Deployment 

This is/will be deployed using GitHub Actions. 
