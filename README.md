#  Disclaimer

This is my personal github page, using Particle Theme with Jekyll.

# Resource

[Visualization (University of Washington)](https://observablehq.com/collection/@uwdata/visualization-curriculum)

* Useful Python Tools
* from pyinstrument import Profiler
* torchsnooper -> pytorch profiling
* knockknock notification

# Instructions

If you are interested to build a page like this. This page using Particle Theme and hosted on Github. You can get yourself a page within 15 minute. Follow these steps if you want.

1. Install Dockers
2. git clone https://github.com/nrandecker/particle , Particle theme that I am using 
3. cd to the repository root directory
4. 	docker run -t --rm -v "$PWD":/usr/src/app -p "4000:4000" starefossen/github-pages
5. go to localhost:4000 or http://192.168.99.100:4000	If you are using Docker Toolbox
6. Edit _config.yml and html under the _includes directory to personalize your site.


# altair viz
* Need to make sure visualization is in JSON format, upload JSON to github repository then reference as URL
* Make sure script for vega is put into the script part
