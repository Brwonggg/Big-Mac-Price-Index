problems that arise and how i fixed it:
initially i wanted to use just the beatifulsoup and requests modules to get the values for the data but then i found that i couldnt do so because the site renders with javascript so my code was unable to read it since it only understands raw html and so i decided to instead use selenium which is capable of running javascript 

had trouble turning the data the prices and the years into a proper dictionary which could be written into a csv file using DictWriter because of the headings/fieldnames

the website i was parsing has a captcha to prove not a robot so i had to swap from selenium to seleniumbase UC mode to bypass it or else the website cant be parsed




## Preview(video demonstration)

## Intro 

## Technologies(tech stack used)

## Running the project(pip install)

## Features (Flow of project)

## Project Structure (How I built it/key files)

## Reasoning Behind Certain Choices (impt)

## Lessons Learnt

## Limitations

## How it can be improved 

(Unit tests)
(Docstrings, type hints, comments)