# data-to-excel

**This is a library for saving data in excel.**

Addendum/Data is saved using the *ExcellSaver* class.  
You can
  - Add new sheet.  
    *ExcellSaver.add_new_sheet(self, cols: list[str], name:str)*, where  
    *cols* - list of column names  
    *name* - name of sheet (default = 'Sheet + {sheet_index}')
    
  - Select an existing sheet.  
    *ExcellSaver.select_sheet(self, index: int)*, where  
    *index* - index of selected sheet
   
  - Add a row to the selected sheet.  
    *ExcellSaver.add_row(self, row: list)*, where  
    *row* - list of row's values
   
  - Create a sheet from added data.  
    *ExcellSaver.create_excel(self, path: str)*, where  
    *path* - path to result file (default = 'result.xmls')
    
