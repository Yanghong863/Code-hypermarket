# Code-hypermarket
>>> import openpyxl
>>> # 创建工作簿
>>> wb = openpyxl.Workbook()
>>> # 创建工作表
>>> ws1 = wb.create_sheet(title = "小甲鱼")
>>> ws2 = wb.create_sheet(title = "不二如是")
>>> ws3 = wb.create_sheet(title = "风介")
>>> ws4 = wb.create_sheet(title = "小泡")
>>> # 个性化工作表
>>> ws1.sheet_properties.tabColor = "FF0000"
>>> ws2.sheet_properties.tabColor = "00FF00"
>>> ws3.sheet_properties.tabColor = "0000FF"
>>> ws4.sheet_properties.tabColor = "8B008B"
>>> # 保存
>>> wb.save(r"C:\Users\goodb\Desktop\test.xlsx")
#guys, this is a punch of code made me confused for several hours, all only what i want to do is create a excel then paint excel title into different color ,please support some tips#
