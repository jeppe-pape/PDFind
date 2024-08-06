# PDFind
 
This is a very simple cmd-line based repo for quickly obtaining search results for a group of PDF's that is pre-ocr'd. Meant to be similar to adobe acrobat find-in-group-of-pdf funcitonality, but loads faster.


### To use:
´´´
pip install PyPDF2
´´´
Place the pdf's you want to search in the "issues" folder.

You input the string you want to search for and a printout will be returned of where (issue, page) the given search string is found in the documents.


### Todo:

- Add OCR functionality for non-scanned pdf's
- Improve interface
- Include standard search options (case-sensitive etc.)
- Object-orient code

### Known bugs

- If search string is found multiple times on given page, only the first is returned
- Ignores non-ascii characters
