# pselc : Select a PDF to open from your terminal
A bash script to display a menu showing all PDF files in a directory and open a user selected PDF.

With the '-s' option, the script can also display PDF files inside subdirectories of the input directory as well.

**Warning**: -s might be slow if you have hundreds of PDFs in a directory
## Installation
1. Clone the repo
2. Make the script executable if it is not already: chmod +x pselc
3. Copy the script to your /usr/local/bin folder to make it available system wide
## Usage
pselc \[options] \[directory]

options : &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-s  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Scan for PDFs in subdirectories as well
  
**Warning**: -s might be slow if you have hundreds of PDFs in a directory
