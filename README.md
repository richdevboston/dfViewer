# dfViewer
A cross-platform PyQt GUI for visualizing pandas dataframes in table format.  Implements some pandas operations,<br>
and includes a GUI for basic plotting with matplotlib.

#### Features:
Currently reads files of the following formats:<br>
  * Excel<br>
  * comma delimited or white-space delimited<br>

Built-in Graph Generator for plotting data <br>
Merge tool for merging multiple dataframes
Group-by tool for selecting subsets of data


#### Requirements:
Python 3.x<br>
pandas<br>
numpy<br>
matplotlib<br>
PyQt4<br>
Or the Anaconda3 distribution<br>

#### Known Issues:
Currently an issue with libpng and at least of of the images used in the tool bar.<br>
<font>libpng warning: iCCP: known incorrect sRGB profile<br>
libpng warning: cHRM: inconsistent chromaticities<br>
libpng warning: iCCP: known incorrect sRGB profile<br>
libpng warning: cHRM: inconsistent chromaticities<br>
PyQT4 is NOT compatible with current version of PyQT5.  This should be run in a legacy PyQT4 virtual environment.  
It will take considerable effort to update this to PyQT5 because many PyQT5 interfaces are different.  See the website here for the differences between PyQT4 and PyQT5:  https://doc.bccnsoft.com/docs/PyQt5/pyqt4_differences.html

#### Screenshots
Main Window<br>
![](./screenshots/dfViewer_main.png)<br>
pandas describe function<br>
![](./screenshots/Describe_Dialog.png)<br>
Graph dialog<br>
![](./screenshots/Graph_Dialog.png)<br>
Group-by dialog<br>
![](./screenshots/GroupBy_Dialog.png)<br>
Merge dialog<br>
![](./screenshots/Merge_Dialog.png)<br>
