# co📁e-XML-File-Handling
A simple yet flexible library to compose or parse XML data in CODESYS based PLC's via the following function blocks;

FB_Filecontrol: provides a generic and easy way to open, close, read, write files without hassle.


FB_StreamBuffer: provides a generic and easy way to compose file contents, this enables you to build your own file content parser more efficiently.


FB_XmlControl: provides a complete solution to read, write, parse and compose xml-based files. 

The solution can handle xml-parsing in two ways: reading an entire file into a pre defined buffer or read file chuncks into a smaller and optimized buffer (as long as the buffer allows for parsing). 

method 1 pro's: fast and relatively easy to implement. con's: large memory required to load the file into the pre-allocated memory buffer

method 2 pro's: wideky applicable due to small memory footprint con's: relative slow parsing of large files. Relatively more complex to implement in comparison with method 1. 

Examples for both parsing methods are provided, which can be used as starting point for your specific needs.

Basic library idea and coding: H.Hermsen, 
bugfixes, testing: i-campbell and Aliazzz,
Additional small memory footprint file parsing: TimvH


MIT Licensed
