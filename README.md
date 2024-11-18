# html-opener-library
Documentation
This library have 1 function

#import library:
from html_opener_library import open_html_periodically

# specify the path to the html file that needs to be opened, the file must be in the same folder with the code
open_html_periodically("sample.html", interval=30)
#"interval=30" this is the part that is responsible for the periodicity of opening html file
