# interactivePV
An interactive web App help you to understand the PV plot data ( for a cryocooler ). 

## How to use
Since the html need to access local data file for the PV plotter, you must setup a web server to server the user ( instead of open the html file straight in web browser ).
One simple way to setup a server is to use the SimpleHTTPServer module from python.
In Python2.x, navigate to the home directory of this project and:
```
$ python -m SimpleHTTPServer [port (default port is 8000)]
```
Or in Python3.x
```
$ python3 -m http.server [port (default port is 8000)]
```
Next, visit the specific html file from a web browser by http://localhost:8000/ .
Now you should be able to choose a sample data file (*.csv) from the input box. Hit start to plot the PV shape and drag the dots to see how PV shape changes.
