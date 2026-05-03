Install the required dependencies:
pip install -U pip
pip install playwright openpyxl
playwright install


Then Running steps
"python image_preview_test.py --url "https://www.pixelssuite.com/crop-image" --slow-mo-ms 4000"


Results
The test results will be automatically appended to execution_results.csv.
Screenshots of the test execution (pass/fail) will be saved in the results directory.
