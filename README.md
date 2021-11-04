# aircraft_scraper.exe
A program to scrape aircraft stats from wikipedia given the name of the aircraft

You must have the .exe file inside a folder with a file name "input.json" with the following format:

{
    "COMMAND": "SCRAPE",
    "TARGET": "F-14"
}

The program will export data to a file named "output.json"

Tested to work with "F-22", "B-17", "B-52", "F-14", "F-15", "Vickers_Valiant", "F-16", "Mig-35", "AC-130", "B-25"
