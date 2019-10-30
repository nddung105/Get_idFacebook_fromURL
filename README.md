# *Code used to convert facebook url to facebook id*
### * Required:
  - python 3.7
  - openpyxl
  - selenium
### * Import file xlsx iclude url facebook. The code has 3 functions: 
  - import_file(path_file) return list link from import file
  - get_id(list_link) return list [url facebook,id facebook]
  - export_data(path_file_export,path_file_import) creaat and write file export is xlsx file include row url and row id
