# Take-Home-Test-CASE02

# Petstore API Collection

## Base URL
https://petstore.swagger.io/v2

## How to Import
1. Download the following files:
   - `TakeHomeTest_CASE02.postman_environment.json`
   - `TakeHomeTest_CASE02.postman_collection.json`
2. Open Postman → **Import** → select both files.

## How to Clone
1. Clone this repository using the following command:
```bash
git clone https://github.com/muhabby/Take-Home-Test-CASE02.git
```

## Requirements
- Newman v6.2.2

## How to Run
1. Open **Command Prompt (cmd)** in the project folder.
2. Run the following command to execute the collection:
```bash
newman run TakeHomeTest_CASE02.postman_collection.json
```
3. To execute the collection and generate an HTML report:
```bash
newman run TakeHomeTest_CASE02.postman_collection.json -r cli,html
```
4. After the execution is completed, the HTML report will be generated automatically in the project directory.