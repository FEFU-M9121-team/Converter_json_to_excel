# Converter_json_to_excel

pip install pandas

pip install openpyxl xlsxwriter xlrd


# Возможно два варианта конвертации - 
1. когда в выборке отслеживаются значения признаков в моментах наблюдения
2. И когда разово зафиксированы ряд признаков(характеристик) со значениями 

# Требования к входному json файлу:
	1.  Формат описаний для всех историй болезней должен быть един (то есть ряд стандартных характеристик больного - это могут быть дата обращения, пол, уникальный номер истории болезни и т.д.)
	2. Описывая ту или иную характеристику в json ожидается поле name, содержащее наименование  характеристики (признака) и поле value,  содержащее значение характеристики 
  3. Вложенность признаков не поддерживается (за исключением случая с моментами наблюдения).
