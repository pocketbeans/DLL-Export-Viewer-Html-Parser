# DLL-Export-Viewer-Html-Parser
Parses .html file output of DLL Export Viewer, which can then be used to create a proxy DLL.

# Usage
Use DLL Export Viewer to generate an html report of any DLL. Pass the html file to the python script and copy the return into your DLL project.

```
python html-parser.py report.html
```

Copy the output into your DLL project. Copy/paste the original DLL into the same folder as your proxy DLL. Rename the original DLL appending a "_orig" to it.
 
