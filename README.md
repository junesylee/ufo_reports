# UFO_Reports_Analysis
Telus Junior Data Scientist

# exercise: ufo reports
http://www.nuforc.org/
For this exercise we provide a data set representing UFO reports accumulated over decades by police officers and later entered into computer forms at police stations. The data is supplied in CSV format and will need to be transformed, summarized, and analyzed in various ways.

## tasks

The sub-tasks are suggestions; if you have something more interesting to do with the data feel free to be creative. Document all the tools/technologies you use for this project. We suggest you load the data in a database and use SQL to extract insights and build your reports and visualizations.

- [ ] Clean the data, e.g.
    - [ ] convert date/time into a standard format, e.g. ISO 3166
    - [ ] convert durations to an interval in seconds
    - [ ] add a country field and store the country in ISO 3166-1
- [ ] Augment the data with external sources, e.g.
    - [ ] use geographic coordinates corresponding to the report location (city/region verification or correction)
    - [ ] see if you can use coordinates to cluster the reports based on location
    - [ ] Identify patterns or anomalies and try to reveal existing insights within the data. Some questions you might want to answer are: Why are the incidents more frequent in some states/cities?
    - [ ] What are some potential drivers for the incidents
- [ ] Analyze the data in various ways, e.g.
    - [ ] bucket the data by date, shape, or location
    - [ ] what trends can you identify in the sightings in each location? How is the trend across different location within a short time period?
    - [ ] find other interesting clusters of sightings
    - [ ] put together an analytics report or visualization based on this data
    - [ ] use the report/visualization to tell stories about the incidents 
- [ ] Transform the data, e.g.
    - [ ] convert to a human-friendly format like HTML
- [ ] Based on the data you have, what is your forecast for January 2020 in terms of volume, object shape, spatial distribution?
  

### fields (required to be provided by the stations. Not a 100% match with the provided data)

- `Occurred`: the date/time at which the sighting occurred
- `Reported`: the date/time at which the sighting was reported
- `Posted`: the date/time at which the sighting was published
- `Location`: city/state
- `Shape`: the reported geometric shape of the observed entity
- `Duration`: the amount of time that the entity was visible
- `city_latitude`, `city_longtitute` geographical coordinates of the city 
- `text`: a free-form text field containing a description of the sighting in the words of the reporter.

### deliverables (all suggestions)

- we suggest github if you like to share your code
- we suggest google cloud platform`s bigQuery if you wanna host your data on a cloud-based database. GCP will give you 300USD allowance to use its cloud platform (which is way higher than what you'd need for this project)
- we suggest Tableau for visualization. You can also use Google Studio which is available with your GCP account and credit
- we suggest you use SQL for your transformations and insight generation. 
