# ASNA Visual RPG Ajax example

```
└── AjaxExample2025.sln/
    ├── VPS.DataNavagationServices/
    │   ├── CustomerByNameList.vr - provides service to get customers by name
    │   └── CustomerByNumberList.vr - not used in this example
    └── WorkWithAjax/
        ├── App_Code/
        │   ├── AutoCompleteItem.vr
        │   ├── CustomerByNameListService.vr
        │   └── CustomerList.ashx.vr
        ├── assets/
        │   ├── css/
        │   │   ├── smoothness - jQuery UI theme/
        │   │   │   └── images
        │   │   ├── CustomerrAutoComplete.css
        │   │   └── main.css        
        │   └── js/
        │       └── three jQuery files 
        ├── Bin/
        │   └── Reference to VPS.DataNavationServices.dll
        ├── services/
        │   └── CustomerList.ashx - generic handler that provides entry point to a service
        ├── views/
        │   └── main/
        │       ├── CustomerAutoComplete.html
        │       ├── Home.aspx
        │       └── SimpleAjaxCall.html
        ├── MasterPage.master
        ├── Web.config
        └── Web.config.authentication      
```        