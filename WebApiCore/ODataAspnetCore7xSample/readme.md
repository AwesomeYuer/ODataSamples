

http://localhost:5000/odata/books?$count=true&$expand=authors,Translators&$filter=Translators/any(x:x/TranslatorID ne 1)