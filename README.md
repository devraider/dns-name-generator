# DNS Name Generator

A Python-based tool to create unique domain names, ideal for finding website or project names.

## Features

- **Random DNS Name Generation**: Combines words and checks if domains are available.
- **Configurable TLD and Length**: Specify the top-level domain (e.g., `.com`) and desired DNS name length.

## Reason or Motivation

Finding an available and relevant domain name can be challenging. This tool aims to simplify the process by quickly generating possible names for websites, projects, or marketing.

## Requirements

This tool requires one or two word lists for generating DNS names by combining entries from each list.

### Creating the Word Lists

1. Create a plain text file with your words, with each word on a new line.
2. Name the files `wordlist1.txt` and `wordlist2.txt` (or similar) if using two lists.

### Placement

Place the word list files in the project root directory (`dns-name-generator`) to ensure the script can access them.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/devraider/dns-name-generator.git
    cd dns-name-generator
    ```
2. Ensure your word lists are prepared and placed in the project directory, then run:
    ```bash
    python auto.py com 10 7
    ```

- `com`: TLD for DNS  
- `10`: Number of DNS names to create  
- `7`: Length of DNS without TLD  

