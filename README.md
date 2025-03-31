This repo is work in progress

**Getting BRUV images ready for SQUIDLE+ code and the associated zip file is currently complete. Other R files are work in progress and will require trouble shooting before use!!!**

This code base is for:

1) Extracting still images from BOSS, BRUV and other video platforms and formatting for upload into SQUIDLE+ using R. 

2) Formatting imagery, metadata and establishing standardised folder structures ready for ingestion into SQUIDLE+ (getting_bruv_images_ready_SQUIDLE+.R) 

3) Extracting annotation data from SQUIDLE+ API using R. This repository provides basic API calls to SQUIDLE+ to download annotations and images for summarizing using R.
NOTE This last code needs updating- will be an R package shortly 
A full list of API endpoints can be found at https://squidle.org/api/help?template=api_help_page.html
4) Making interactive maps based on SQUIDLE+ API and Seamap Australia geoserver layers

Getting Started:
1. Prerequisites
Ensure you have R installed on your system. You will also need the httr, jsonlite, tidyverse, leaflet, leaflet.extras,
magick, htmlwidgets, glue packages. 


Reporting Issues:

If you encounter any errors or issues with the R code, please report them to jacquomo.monk@utas.edu.au.

This project is licensed under the MIT License:

Copyright (c) 2024 Jacquomo Monk

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
