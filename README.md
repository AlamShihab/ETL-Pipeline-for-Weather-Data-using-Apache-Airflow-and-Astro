# ETL-Pipeline-for-Weather-Data-using-Apache-Airflow-and-Astro

This project leverages Apache Airflow for orchestration and was generated after running astro dev init using the Astronomer CLI. This README describes the contents of the project, how Airflow is used within it, and how to run the stack locally.

#Project Contents
This project contains the following files and folders:

#dags/
Contains the Python files for the Airflow DAGs. By default, this directory includes one example DAG:

#example_astronauts
This DAG demonstrates a simple ETL pipeline that queries the list of astronauts currently in space (via the Open Notify API) and prints a statement for each astronaut. It uses the TaskFlow API to define tasks in Python, and leverages dynamic task mapping to handle each astronaut’s data. For more details on how this DAG operates, see the Getting started tutorial.

#Dockerfile
Specifies a versioned Astro Runtime Docker image that provides a tailored Airflow experience. 


#packages.txt
Install OS-level packages required by the DAGs or custom operators by listing them here. This file is empty by default.

#requirements.txt
Install Python packages (e.g., specific Airflow provider packages or custom libraries) needed for this project by adding them to this file. It is empty by default.

#plugins/
Add custom or community Airflow plugins—hooks, operators, sensors, etc.—here. This directory is empty by default.

#airflow_settings.yaml
A local-only file to specify Airflow Connections, Variables, and Pools. Instead of manually entering settings via the Airflow UI as you develop DAGs, you can declare them here so they automatically load when Airflow starts.
