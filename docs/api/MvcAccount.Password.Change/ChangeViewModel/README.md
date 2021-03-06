ChangeViewModel Class
=====================
Holds data for the Change view.


Inheritance Hierarchy
---------------------
[System.Object][1]  
  [MvcAccount.Shared.BaseViewModel][2]  
    [MvcAccount.Shared.FormViewModel][3]&lt;[ChangeInput][4]>  
      **MvcAccount.Password.Change.ChangeViewModel**  

**Namespace:** [MvcAccount.Password.Change][5]  
**Assembly:** MvcAccount (in MvcAccount.dll)

Syntax
------

```csharp
public class ChangeViewModel : FormViewModel<ChangeInput>
```

The **ChangeViewModel** type exposes the following members.


Constructors
------------

                 | Name                 | Description                                                                              
---------------- | -------------------- | ---------------------------------------------------------------------------------------- 
![Public method] | [ChangeViewModel][6] | Initializes a new instance of the [ChangeInput][4] class using the provided input model. 


Methods
-------

                 | Name                    | Description                                                                                                                                           
---------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- 
![Public method] | [HtmlHelperForInput][7] | Returns a [HtmlHelper&lt;TModel>][8] to be used to render form controls for the [InputModel][9]. (Inherited from [FormViewModel&lt;TInputModel>][3].) 


Properties
----------

                      | Name               | Description                                                                                        
--------------------- | ------------------ | -------------------------------------------------------------------------------------------------- 
![Public property]    | [CancelText][10]   | Text for the cancel button. (Inherited from [FormViewModel&lt;TInputModel>][3].)                   
![Public property]    | [InputModel][9]    | The form's input model. (Inherited from [FormViewModel&lt;TInputModel>][3].)                       
![Public property]    | [SubmitText][11]   | Text for the submit button. (Inherited from [FormViewModel&lt;TInputModel>][3].)                   
![Public property]    | [Title][12]        | The view's title, used on h1 and title elements. (Inherited from [BaseViewModel][2].)              
![Protected property] | [Url][13]          | A [UrlHelper][14] for creating URLs. (Inherited from [BaseViewModel][2].)                          
![Public property]    | [ViewCssClass][15] | A space-separated list of CSS classes to be used in the view. (Inherited from [BaseViewModel][2].) 


See Also
--------

#### Reference
[MvcAccount.Password.Change Namespace][5]  

[1]: http://msdn.microsoft.com/en-us/library/e5kfa45b
[2]: ../../MvcAccount.Shared/BaseViewModel/README.md
[3]: ../../MvcAccount.Shared/FormViewModel_1/README.md
[4]: ../ChangeInput/README.md
[5]: ../README.md
[6]: _ctor.md
[7]: ../../MvcAccount.Shared/FormViewModel_1/HtmlHelperForInput.md
[8]: http://msdn.microsoft.com/en-us/library/dd492619
[9]: ../../MvcAccount.Shared/FormViewModel_1/InputModel.md
[10]: ../../MvcAccount.Shared/FormViewModel_1/CancelText.md
[11]: ../../MvcAccount.Shared/FormViewModel_1/SubmitText.md
[12]: ../../MvcAccount.Shared/BaseViewModel/Title.md
[13]: ../../MvcAccount.Shared/BaseViewModel/Url.md
[14]: http://msdn.microsoft.com/en-us/library/dd492578
[15]: ../../MvcAccount.Shared/BaseViewModel/ViewCssClass.md
[Public method]: ../../_icons/pubmethod.gif "Public method"
[Public property]: ../../_icons/pubproperty.gif "Public property"
[Protected property]: ../../_icons/protproperty.gif "Protected property"