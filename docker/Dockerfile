# Miniconda image as base image
FROM continuumio/miniconda3

# Updates
RUN apt-get update && apt-get install -y

# Set working directory
# WORKDIR /workspaces/$Project-Folder
WORKDIR /workspaces/data-science-template

COPY . .

# Create the conda environment
RUN conda env create --file environment.yml