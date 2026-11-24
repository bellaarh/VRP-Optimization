# Excel Hackathon: Vehicle Routing Problem (VRP) Optimization

## Project Overview
This project is my official submission for the DQLab Hackathon, focusing on solving the Vehicle Routing Problem (VRP) using Microsoft Excel. 

As a fresh graduate pivoting my career into Data Analytics, this project shows how I handle complex logistics data, apply constraint-based optimization, and solve real-world supply chain efficiency problems.

## The Challenge & Objective
A logistics operations setup has 50 delivery locations with a total package demand of 259 units. The goal is to deliver all packages from a central depot using a fleet of **10 trucks** (each with a maximum capacity of 28 units) while keeping the total travel distance as short as possible.

## How I Solved It
I built a structured tracking system and used advanced optimization in Excel:
* Excel Solver: Configured the mathematical constraints that ensure no truck overloaded past 28 units and finding the best logical sequence for the routes.
* Route Segments (AllDiff Decision Variables): Used specific indexing so every location is visited exactly once without overlaps.

## Results
* Total Optimized Distance: Managed to lower the total fleet travel distance down to 1,192.49 km.
* Fleet Utilization: All 10 trucks were successfully routed within their safe capacity limits (max 28 units per truck), creating an organized, zero-overload delivery plan.
