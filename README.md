# DAT-129_robert
fall 21 python 2 at CCAC
## JSON Project  
module name - json_project.ipynb.
Overview -  The module reads two input files: a json file that contains search criteria and a CSV data file. 
            Returns the results of the search in a JSON file.
## Inputs
The module prompts the user for the input file path names. The first file is the CSV data file that will be searched and the second
file is a json file that contains search criteria. 
## Output
The results from the search is returned in a JSON file. 
## Example of search Criteria
{
	"search_value_1": {
		"field_name": "Lowest",
		"field_value": "23000",
		"field_action": ">"
		},
	"search_value_2": {
		"field_name": "Second",
		"field_value": "45000",
		"field_action": ">"
		}
}

Allowable field action values: <, >, =, <= and >=
