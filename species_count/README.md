<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>

<!-- ABOUT THE PROJECT -->

# Species Count

The <a href="https://www.iucnredlist.org/resources/spatial-data-download">dataset</a> we use for species count code is provided by IUCN. The IUCN Red List of Threatened Species™ contains global assessments for more than 157,100 species. More than 83% of these (>130,500 species) have spatial data. For each species, the dataset provide the known range of it, in ploygon format.

Given a ploygon of an area, our script will first generate grids within in that area, here we can specify the resolution. Then for each grid, we will get the number of species that occurs in that grid, and return that number as the value of that grid.

To sum up, given an area and a resolution, the script will generate a species abundance plot, or a geotiff file if you like.

### Getting Started

There are 3 files:

1. 'helper.py' contains all functions needed for computation. You don't need to modify it if you just want to run the script.
2. 'All Species Count.ipynb' is the main entry. You can change inputs here.
3. 'output_tiff.ipynb' is an example of how to generate tiff file as output. It will be removed later.

To run the script, all you need to do is to look at 'All Species Count.ipynb'.

1. Make sure the input file path is correct, both the files for the dataset and input polygon.
2. Make sure the output file path is as you expect.
3. You can specify the resolution. And if you want to specify species, change the files in the input folder. The script will only include species whose files are in the input directory.

# Sea Level

The script is operating on <a href="https://sealevel.nasa.gov/ipcc-ar6-sea-level-projection-tool">NASA sea level change data</a>. The code structure is not complex, and codes are well-commented. Please refer to the ipynb file.
