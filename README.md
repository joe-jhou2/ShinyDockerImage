# Shiny Seurat Docker Image

This repository contains a Dockerfile for building a Docker image that includes 
R, Shiny, and Seurat, along with other useful R packages. The images can be pulled 
from Docker Hub:  `jhoufred/joe-shiny-seurat`.

## Overview

- **Base Image**: This Docker image is built based on the `rocker/shiny` image.

- **Seurat Integration**: Includes crucial packages to support and utilize the 
                          Seurat package effectively.
                          
- **Enhanced Capabilities**: Incorporates supplementary packages for features 
                             like email services and user management.
                             
- **Database Support**: Provides built-in support for MySQL databases.

- **Accessibility**: The image can be accessed and downloaded from Docker Hub: 
                      `jhoufred/joe-shiny-seurat`.
                      

## Included Packages
Seurat package:

- **SeuratObject**

- **Seurat**

Data processing

- **tidyverse**

- **tidydr**

Database:

- **DBI**

- **RMySQL**

Email service:

- **mailR**

- **uuid**

Visuliazation: 

- **ComplexHeatmap**

- **circlize**

- **ggh4x**

- **ggpubr**

Others:

- **shinyWidgets**

- **rJava**

- **pool**

- **dotenv**

## Usage

To run the Docker container, use the following command:

`docker run -it --rm -p 3838:3838 jhoufred/joe-shiny-seurat`