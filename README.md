# ChargingProfileGeneratorV2

Brief description of the project.

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Getting Started](#getting-started)
    - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

Given user settings, and car data this console application calculates the optimal schedule for the user from a given
moment (the StartingTime) until the Leaving Time. Optimize on lowest energy bill for the user

## Features

The project will also print the result when run to the output JSON file.
You are able to change the input Json files data and the project will calculate based on that data.

## Getting Started

1. Clone the repository to your local machine using the following command: 
   git clone <repository_url>

2. Open the solution file in your preferred IDE (e.g., Visual Studio, Visual Studio Code).


### Installation

Once the project has been cloned and open in your prefered IDE.

Confirm that you have the Newtonsoft extension installed to do so do the following:

To do so, in Visual Studio -> project -> Manage NuGet Packages... -> and search for Newtonsoft

## Usage

When you run the program you will be presented with a console displaying 3 things:

- The Start date
- The End date
- And if it is charging (True or False)

The above data is then writen to a Json file called the OutputJsonFile.

If you wish to see how the program performs when presented with different DateTimes, Tariff rates and car data then you can do this by editing
the InputJsonFile data and then rerunning the program.
