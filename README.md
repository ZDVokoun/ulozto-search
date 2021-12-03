# ulozto-search
Search uloz.to for files using Python. It only supports one-page query for now. 

## Usage

``` python
import ulozto_search

query = "your_query"
file_type = "documents|videos|images|archives|audios"  # optional

# search and return dictionary
ulozto_search.search(query, file_type)

# search and return HTML string
ulozto_search.searchHTML(query, file_type)
```

It can be also used from terminal:

```
$ python ulozto_search.py
Enter your query: hello 
Enter file type: 
hello.txt | https://uloz.to/file-tracking/...
...
```
