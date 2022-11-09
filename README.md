# Welcome to my Data Skills Challenge!
In this repository, the RStudio file and HTML file can be found for my Data Skills Challenge project.
 
When running my R Notebook file, keep in mind the following:

1. Open my project folder as a project in RStudio to ensure my file paths work.
2.  You may need to install the package 'sf'. Type install.packages("sf") into your console.
3. To use the package tidycensus, you may need to install the package in an alternate manner. First, install the packages 'remotes' with install.packages("remotes"), and then type remotes::install_github("walkerke/tidycensus") to install the package.
4. You need a Census API key to use tidycensus. To obtain a census API key, go to https://api.census.gov/data/key_signup.html. Then, run census_api_key("YOUR API KEY GOES HERE"), replacing your given API key for "YOUR API KEY GOES HERE". You should be able to run the code from here on out.  
