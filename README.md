# Suffix Tree Analyzer

## Overview
**Suffix Tree Analyzer** is a Racket-based project designed to construct and analyze suffix trees for efficient string pattern matching and text processing tasks. Suffix trees are powerful data structures that facilitate fast substring searches, making them valuable in various applications such as bioinformatics, text editing, and data compression.

## Features
- **Suffix Tree Construction:** Efficiently builds suffix trees for given input strings.
- **Pattern Matching:** Allows for quick searches of substrings within large texts.
- **Multi-Stage Processing:** Implements a series of transformation stages to process and analyze textual data.

## Project Structure
- `suffix-tree.rkt`: Contains the core implementation for constructing and manipulating suffix trees.
- `etapa1.rkt`: First stage of text processing, focusing on initial data transformations.
- `etapa2.rkt`: Second stage, refining the processed data for further analysis.
- `etapa3.rkt`: Final stage, applying advanced transformations and optimizations.
- `checker.rkt`: Module designed for validating the correctness of the suffix tree and processing stages.

## Installation
To run this project, ensure you have [Racket](https://racket-lang.org/) installed on your system. Clone the repository using the following command:
```sh
git clone https://github.com/TeodoraTeo05/Suffix-Tree-Analyzer.git
cd Suffix-Tree-Analyzer
```

## Usage
Execute the Racket scripts in sequence to perform the full analysis:
```sh
racket etapa1.rkt
racket etapa2.rkt
racket etapa3.rkt
```
To construct and analyze a suffix tree for a specific input, run:
```sh
racket suffix-tree.rkt
```

## Example
Given an input string, the `suffix-tree.rkt` script will output the constructed suffix tree and allow for efficient pattern matching operations.
