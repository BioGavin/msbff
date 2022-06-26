# MASS Bioactive Fractions Filtering

## Install

MS-BFF package has been uploaded to PyPI, so you can install it by pip conveniently.

```bash
pip install msbff
```



## Main Function

- Module 1 Preprocessing data: Read data and perform data cleaning

- Module 2 Processing data: Calculate each variable value.

- Module 3 Data visualization: Plot one line chart and three heatmap.



## Usage

### Help

Run the command and view the help information.

```bash
msbff -h
```



### Example

You can run the command with the default parameters and the output files will be saved in a specified folder.

```bash
mkdir output  # create output folder
msbff -i rawdata.csv -o output  # run msbff in default
```



### Output Files

- `data_extraction.csv`: The data obtained by filtering the input raw data according to the requirements.
- `block_score.csv`: Percentage of the sum of Pearson correlation coefficients (PCC) within each block.
- `max_inhibition_rate.csv`: Maximum value of Pearson correlation coefficient (PCC) within each block.
- `relative_signal_intensity.csv`: Percentage of the sum of S/N average within each block.

- `Fig.png`: Visualization results of the above three tables of data.



## Contact

Don't hesitate to contact me by email if you have any problems.

E-mail: gavinchou64@gmail.com