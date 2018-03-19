## Synopsis 
The project is a data visualization telling a story of the delayed flights in 30 major airports across USA in 2017.

## Demo 

<strong>Interface</strong>
![Demo](https://user-images.githubusercontent.com/23627710/37572902-3bd18674-2acf-11e8-8c91-e5eb058b17e9.png)

<strong>Interaction</strong>
![Demo](https://user-images.githubusercontent.com/23627710/37572844-688da478-2ace-11e8-80ce-334cfab89404.gif)

## Data Resource 
<a href = "https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp">Bureau of Transportation Statistics </a>


## Loading File Locally

According to <a href="https://github.com/d3/d3/issues/1698">Mike Bostock's comment in 2014</a>, "Chrome disallows XMLHttpReques when running files from the local file system (file:///)".  Due to this limitation, without loading the file via a local server, the US map written in Topo JSON won't display on the screen.

To load the file, you will need to start a local service on your computer.

Step1: Download Python3;</br>
Step2: Navigate to the project (use "cd projectDirectory")</br>
Step3: Type in "python -m http.server";</br>
Step4: Type "localhost:8000" in browser;</br>
Optional: If the default protocol 8000 is in use, you can switch to another protocol by typing "python -m SimpleHTTPServer 8910" .

After the initial setup, you need to activate the local service before you load the file.

Step1: Navigate to the project;</br>
Step2: Type in "python -m http.server" when using the default protocol 8000;</br>
Optional: Type in "python -m SimpleHTTPServer 8910" when your protocol is switched to 8910.

## Code Reference 
The code referred to <a href="https://bl.ocks.org/mbostock/4090848">U.S. States TopoJSON</a>, <a href="http://bl.ocks.org/michellechandra/0b2ce4923dc9b5809922">Basic US State Map</a>, <a href="http://bl.ocks.org/micahstubbs/8e15870eb432a21f0bc4d3d527b2d14f">World Map 02 Update to d3 v4</a>, <a href="http://bl.ocks.org/Caged/6476579">Using d3-tip to add tooltips to a d3 bar chart</a>, <a href="http://bl.ocks.org/williaster/10ef968ccfdc71c30ef8">Updating bar chart with dropdown</a>


## License 
Released under <a href = "https://opensource.org/licenses/MIT"> The MIT License </a>