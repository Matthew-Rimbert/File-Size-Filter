# File Size Finder

This Python script provides a utility to list files within a specified root folder and its subfolders based on size conditions, making it easy to manage and analyze file storage.

## Features

- Browse through directory hierarchy.
- Filter files based on size comparison (`=`, `>`, `<`).
- Print details (filename, size, creation date) of files meeting the specified condition.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.

### Installation

Clone this repository to your local machine using:

```bash
git clone https://github.com/yourusername/file-size-finder.git
```
### Usage
1. Open your terminal or command prompt.
2. Navigate to the directory containing the script. If you cloned the repository, it might look something like this:
```bash
cd path/to/file-size-finder
```
3. Run the script using the Python interpreter. You can start the script with the following command:
```bash
python w5_matthew_rimbert.py
```
### Interactive Prompts
Once the script is running, you will need to input several pieces of information:

- **Root Folder Path**:<br>
Enter the path to the root folder you wish to analyze.
  - Example: C:\Users\YourName\Documents.<br>
- **Size Operator**:
Input the operator for filtering file sizes **(=, >, <)**.
  - For instance, entering > will filter for files larger than the specified size.<br>
- **Target Size**:
Provide the file size in bytes to compare against.<br>
  - Example: 1000 for 1000 **bytes**.<br>

### Example
Here's a **step-by-step** example of how to run the script:
```bash
Enter the root folder path: C:\Users\YourName\Documents
Enter the size operator ('=', '>', or '<'): >
Enter the target size (in bytes): 1000
```
This will display files in the specified directory that are greater than 1000 bytes, along with their names, sizes, and creation dates.

![File_Size_Finder_Script](https://github.com/Matthew-Rimbert/File-Size-Finder/assets/169205418/f4ec112e-b0a5-448d-924e-7eab6654439d)




