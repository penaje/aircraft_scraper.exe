# aircraft_scraper.exe
A program to scrape aircraft stats from wikipedia given the name of the aircraft

You must have the .exe file inside a folder with a file name "input.json" with the following format:

{
    "COMMAND": "SCRAPE",
    "TARGET": "F-14"
}

The program will export data to a file named "output.json"

Tested to work with "F-22", "B-17", "B-52", "F-14", "F-15", "Vickers_Valiant", "F-16", "Mig-35", "AC-130", "B-25"

Output format:

{"COMMAND": "SCRAPE_SUCCESS",
"TARGET": {"CREW": "2 ( Pilot and Radar Intercept Officer )", "LENGTH": "62 ft 9 in (19.13 m)", "WINGSPAN": "64 ft 1.5 in (19.545 m)", "SWEPT WINGSPAN": "38 ft 2.5 in (11.646 m) swept", "WING AREA": "565 sq ft (52.5 m 2 ) wings only 1,008 sq ft (94 m 2 ) effective area including fuselage ", "ASPECT RATIO": "NULL", "MAX TAKEOFF WEIGHT": "74,350 lb (33,725 kg)", "POWERPLANT": "2  General Electric F110 -GE-400 afterburning turbofans , 16,610 lbf (73.9 kN) thrust each dry, 28,200 lbf (125 kN) with afterburner ", "MAXIMUM SPEED": "Mach 2.34 (1,544 mph, 2,485 km/h) at altitude", "FERRY RANGE": "NULL", "RANGE": "1,600 nmi (1,800 mi, 3,000 km)", "COMBAT RANGE": "500 nmi (580 mi, 930 km)", "WING LOADING": "96 lb/sq ft (470 kg/m 2 )  48 lb/sq ft (230 kg/m 2 ) effective ", "THRUST/WEIGHT": ": 0.92 at gross weight (1.07 with loaded weight & 50% internal fuel)", "GUNS": "1 20 mm (0.787 in) M61A1 Vulcan 6-barreled Gatling cannon , with 675 rounds", "HARDPOINTS": "10 total: 6 under-fuselage, 2 under nacelles and 2 on wing gloves   with a capacity of 14,500 lb (6,600 kg) of ordnance and fuel tanks  ,", "ROCKETS": "7x LAU-10 rocket pods (for a total of 28 rockets)", "OTHERS": "Tactical Airborne Reconnaissance Pod System (TARPS) LANTIRN Targeting System (LTS) pod (AN/AAQ-14) 2 267 US gal (1,010 l; 222 imp gal) drop tanks for extended range/loitering time", "MISSILES": "Air-to-air missiles: AIM-54 Phoenix , AIM-7 Sparrow , AIM-9 Sidewinder", "LOADING CONFIGURATIONS": "2 AIM-9 + 6 AIM-54 (Rarely used due to weight stress on airframe) 2 AIM-9 + 2 AIM-54 + 3 AIM-7 (Most common load during Cold War era) 2 AIM-9 + 4 AIM-54 + 2 AIM-7 2 AIM-9 + 6 AIM-7 4 AIM-9 + 4 AIM-54 4 AIM-9 + 4 AIM-7", "BOMBS": "JDAM precision-guided munition (PGMs) Paveway series of laser-guided bombs Mk 80 series of unguided iron bombs Mk 20 Rockeye II cluster munition"}}
