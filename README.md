# GPA - Genome Profile Alignment

Detailed description will follow soon.

## Dependencies

* progressiveMauve
* Java Virtual Machine


## Usage

<code>$ java -jar GPA.jar [GPAconfig File]</code>


## Config File Parameters

The config file has to contain the following information:

* progressiveMauve executable location
* directory for output 
* directory containing the genome file in fasta-format
* guide tree (Parsnp & progressiveMauve are currently supportet)
* maximal merge size for guide tree compression 

An Example for the config file structure with the respective entries is contained in this git


## Output

After computation the output contain the 