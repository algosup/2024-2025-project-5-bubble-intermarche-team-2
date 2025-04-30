<div align=center>

# Technical Specification

---

**Project Name**: Bubble Intermarché <br>
**Team**: Team 2 <br>
**Created by**: Enoal ADAM <br>
**Creation Date**: 04/29/2025 <br>
**Updated**: 04/29/2025 <br>

---

</div>

<details>
<summary>Table of Contents</summary>

- [Technical Specification](#technical-specification)
  - [1. Introduction](#1-introduction)
  - [2. Objectives](#2-objectives)
  - [3. GitHub Folder Structure](#3-github-folder-structure)
  - [4. Conventions](#4-conventions)
  - [5. Requirements](#5-requirements)

</details>

## 1. Introduction

The project goal is to develop with the Bubble technology[^1] a web application for the Intermarché St-Rémi-de-Provence supermarket. The application will allow customers to find cheeses and wines that pair well with the dishes they want to prepare (related to the ingredients there are in them). The application will be available in French as well as English.

## 2. Objectives

- 
- 
- 
- 
- 

## 3. GitHub Folder Structure

``` bash
2024-2025-project-5-bubble-intermarche-team-2
├── .github # GitHub folder for the project
│   ├── workflows # GitHub Actions folder -> Contain the scripts that will automatically run
│   │   └── main.yml # GitHub Actions script to merge the main branch into the sub-branches
│   │
│   └── ISSUE_TEMPLATE # GitHub issue template folder -> Contains the templates for issues
│
├── Documents # Stores all the documents related to the project
│   ├── Functional
│   │  ├── Images
│   │  └── functional_specification.md
│   │
│   ├── Technical
│   │  ├── Images
│   │  └── technical_specification.md
│   │
│   ├── Quality_Assurance
│   │  ├── Images
│   │  └── test_plan.md
│   │
│   ├── Management
│   │  ├── Images
│   │  ├── Management_Artifacts
│   │  └── Weekly_Reports
│   │
│   └── User_Manual
│      ├── Images
│      └── user_manual.pdf
│
├── Src # Stores the link to the Bubble project (since Bubble is a no-code platform)
│  └── bubble_project.md # Change this file name when we'll know how to name it
│
├── .gitignore # Ignore files and folders in the repository
└── README.md # Project description and instructions to run the project
```

## 4. Conventions

To ensure the coordination of the document, names and so on, conventions are set up in this project. Below are the conventions used in this project:

| Type              | Example Name          | Convention        |
| ----------------- | --------------------- | ----------------- |
| Files             | `file_name`           | snake_case        |
| Folders           | `Folder_Name`         | Pascal_Snake_Case |
| Document Titles   | `Wonderful Title`     | Title Case        |
| Web Pages         | `one_Page`            | camel_Snake_Case  |
| Group of Elements | `Answers Group`       | Title Case        |
| States            | `the_Best_State`      | camel_Snake_Case  |
| Databases         | `Incredible_Database` | Pascal_Snake_Case |
| Fields (Data)     | `best_data_ever`      | snake_case        |
| API Calls         | `GoodNameOfAPI`       | PascalCase        |

> [!caution] Elements Naming Conventions
> To avoid all misunderstandings regarding to an element in Bubble, the name of the element must be in **Title Case** preceded by its type (except for groups). <br>
> For example, if the element is an *Input*, its name should be "Input Zip Code".

<br>

## 5. Requirements

Before going further, it is highly recommended to read the [Functional Specification](../Functional/functional_specification.md) document. It contains all the necessary information about the requirements and can also help in understanding the rest of this document. <br>

