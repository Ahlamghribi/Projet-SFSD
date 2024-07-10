# Medicament Management System

## Overview

This project implements a basic system for managing a list of medications using C. It includes functionalities to store, display, and delete medication records. The data is stored in binary files, and each medication record includes details such as name, quantity, price, reference number, and fabrication and expiration dates.

## Features

- **Store Medication Data**: Convert and store medication details in a binary file.
- **Display Medication Data**: Read and display medication details from a binary file.
- **Delete Medication Record**: Remove a medication record from the binary file.

## Data Structures

- **`date`**: Structure to store date information.
- **`location`**: Structure to store the location of a record in the file.
- **`Medicament`**: Structure to store medication details.
- **`Bloc`**: Structure to store a block of records.
- **`Index`**: Structure to store indexing information.
- **`entete`**: Structure to store metadata about the file (number of records and blocks).

## Functions

- **`taillenrg`**: Calculates the size of a record.
- **`taillebloc`**: Calculates the size of a block.
- **`tochar`**: Converts a `Medicament` structure to a character array.
- **`afficher`**: Displays the details of a medication record.
- **`Suppression`**: Deletes a medication record from the file.

## Usage

1. **Store Medication Data**:
    - Convert medication details to a character array and store it in a binary file.
  
2. **Display Medication Data**:
    - Read and display medication details from the binary file.

3. **Delete Medication Record**:
    - Remove a medication record from the binary file based on its reference number.
