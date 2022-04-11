# sitesmapgather
A jupyter notebook to gather gather sitemaps and save as csv

## ToDo

- [x] put all files into subdir with same name as domain
- [x] add user agent to avoid refusal of download
    - credits:
    - https://www.shellhacks.com/python-requests-user-agent-web-scraping/
- [x] add date to subdir name to avoid overwriting
- [ ] auto check if online xml or local csv, so we don't have to specify that ourselves
- [ ] auto check if sitemap index file or not
- [x] merge csv files
    - credits:
    -  https://softhints.com/how-to-merge-multiple-csv-files-with-python/
- [ ] delete .xml files
- [ ] add UI
    - [ ] user selectable directory to save csv's in
- [ ] recursion - submit a list of sitemap index files and get everything within them
- [ ] bug: UnicodeDecodeError: 'charmap' codec can't decode byte 0x81 in position 1112525: character maps to <undefined>
    - during https://www.tv2.no/sitemap/sitemap.xml