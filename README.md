# *Code used to convert facebook url to facebook id*
### * Required:
  - python 3.7
  - openpyxl
  - selenium
### * Import file xlsx iclude url facebook. The file covert_url_id.py has 3 functions and use https://lookup-id.com: 
  - import_file(path_file) return list link from import file
  - get_id(list_link) return list [url facebook,id facebook]
  - export_data(path_file_export,path_file_import) creaat and write file export is xlsx file include row url and row id
### The file covert_url_id_.py search id directly through the login:
  - get_id(email,pass_,list_link) add 2 parameters email and pass_ are username and password your Facebook 
