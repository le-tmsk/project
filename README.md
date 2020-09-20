### PROJECT SWIMPLACES

Tláskalová & Tomášková

In our project, we download data from website www.swimplaces.com. We gather information about places where to swim and visualize it.

File __data_downloader.ipynb__ contains a class which downloads information from API and from each place's webpage. The downloading itself takes about 1 hour due to high number of pages and searching through text. Data are stored in a csv file. File raw_data.json is only as a secondary solution in case the API changes its reaction.

In file __Data_Interpretation.ipynb__, data are cleaned and processed into desired format. Descriptive statistics are provided, followed by data visualization. User can find 5 nearest places where to swim by inserting his location. An example is provided for city Litomyšl.
