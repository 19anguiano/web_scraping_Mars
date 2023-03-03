# web_scraping_Mars
![mars_1](https://user-images.githubusercontent.com/119361768/222659098-afd84f8a-c20b-4429-af82-66e431c442cb.jpg)


# Deliverables

## Deliverable 1
### Scrape Titles and Preview Text 
Titles and preview text from Mars news articles:
    
         [{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
        'preview': 'For the first time in its eight years orbiting Mars, NASA’s MAVEN mission 
        witnessed two different types of ultraviolet aurorae simultaneously, the result of 
        solar storms that began on Aug. 27.'},
       {'title': "NASA Prepares to Say 'Farewell' to InSight Spacecraft",
        'preview': 'A closer look at what goes into wrapping up the mission as the spacecraft’s 
        power supply continues to dwindle.'},
       {'title': 'NASA and ESA Agree on Next Steps to Return Mars Samples to Earth',
        'preview': 'The agency’s Perseverance rover will establish the first sample depot on 
        Mars.'},
       {'title': "NASA's InSight Lander Detects Stunning Meteoroid Impact on Mars",
        'preview': 'The agency’s lander felt the ground shake during the impact while cameras 
        aboard the Mars Reconnaissance Orbiter spotted the yawning new crater from space.'},
       {'title': 'NASA To Host Briefing on InSight, Mars Reconnaissance Orbiter Findings',
        'preview': 'Scientists from two Mars missions will discuss how they combined images and 
        data for a major finding on the Red Planet.'},
       {'title': 'Why NASA Is Trying To Crash Land on Mars',
        'preview': 'Like a car’s crumple zone, the experimental SHIELD lander is designed to 
        absorb a hard impact.'},
       {'title': 'Curiosity Mars Rover Reaches Long-Awaited Salty Region',
        'preview': 'After years of climbing, the Mars rover has arrived at a special region 
        believed to have formed as Mars’ climate was drying.'},
       {'title': 'Mars Mission Shields Up for Tests',
        'preview': 'Protecting Mars Sample Return spacecraft from micrometeorites requires 
        high-caliber work.'},
       {'title': "NASA's InSight Waits Out Dust Storm",
        'preview': 'InSight’s team is taking steps to help the solar-powered lander continue 
        operating for as long as possible.'},
       {'title': "NASA's InSight 'Hears' Its First Meteoroid Impacts on Mars",
        'preview': 'The Mars lander’s seismometer has picked up vibrations from four separate 
        impacts in the past two years.'},
       {'title': "NASA's Perseverance Rover Investigates Geologically Rich Mars Terrain",
        'preview': 'The latest findings provide greater detail on a region of the Red Planet 
        that has a watery past and is yielding promising samples for the NASA-ESA Mars Sample 
        Return campaign.'},
       {'title': 'NASA to Host Briefing on Perseverance Mars Rover Mission Operations',
        'preview': 'Members of the mission will discuss the rover’s activities as it gathers 
        samples in an ancient river delta.'},
       {'title': "NASA's Perseverance Makes New Discoveries in Mars' Jezero Crater",
        'preview': 'The rover found that Jezero Crater’s floor is made up of volcanic rocks 
        that have interacted with water.'},
       {'title': "10 Years Since Landing, NASA's Curiosity Mars Rover Still Has Drive",
        'preview': 'Despite signs of wear, the intrepid spacecraft is about to start an 
        exciting new chapter of its mission as it climbs a Martian mountain.'},
       {'title': "SAM's Top 5 Discoveries Aboard NASA's Curiosity Rover at Mars",
        'preview': '“Selfie” of the Curiosity rover with inset showing the SAM instrument prior 
        to installation on the rover.'}]
  

## Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
### Mars DataFrame
![df](https://user-images.githubusercontent.com/119361768/222656995-14459e00-ee75-46ba-9ba5-3fe4fdeeb611.png)

Full DataFrame can be found in Mars Analysis > mars_table.csv

### Analysis
1. There are 12 months on Mars
2. There are 1,867 Martian days' worth of data.
3. The coldest month is month number 3 at -83.31 degrees. The hottest month is month number 8 at -68.38 degrees. These are the average low temperatures by month: 

![download](https://user-images.githubusercontent.com/119361768/222657866-f1f9fce3-a029-48be-9660-a066b672d1d1.png)

4. Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.

![download](https://user-images.githubusercontent.com/119361768/222658187-b0664716-cb15-4a04-9243-acd862e9e6e9.png)

5. The distance from peak to peak is roughly 1450 minus 775, or 675 days. A year on Mars appears to be about 675 days from the plot.

![download](https://user-images.githubusercontent.com/119361768/222658331-6b7b3577-25ca-4b56-8a0a-f4a3faf99d3c.png)

