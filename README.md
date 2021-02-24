# Extract, Transform, Load

## Source
Master's in Data Science Website

## Extraction Methods
* Requests to get the HTML from the website
* BeautifulSoup to parse the HTML

## Transformation Methods
* Use Pandas to convert list of dictionaries to a dataframe and fix formatting

## Load Methods
* Use SQLAlchemy and Pandas to send the dataframe to a PostgreSQL database

## Final Production Database
Relational (PostgreSQL)

## Key Takeaways

**What could this data be used for in the future?:**
Seeing what programs are available at a glance and what schools have what types of programs.

**How often should we pull the data?:**
Because this is data that most likely wouldn’t change often, we could have it pulled every 3 months to see if classes have changed or if new classes have been added.

**What can be examined of the data over time?:**
Over time we can see if the average wage has changed for the different masters programs based on location. We can also determine if projected job change will increase or decrease for each program over time.

**Who would benefit from seeing a breakdown of the data?:**
This could be a great breakdown for students looking to decide what masters programs to get in to. This could also benefit anyone in the academic field to see if what they are teaching has real life applications. 

