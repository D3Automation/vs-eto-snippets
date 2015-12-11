# vs-eto-snippets
Code snippets to use with ETO in Visual Studio

# Installation
Clone this repository into %USERPROFILE%\Documents\Visual Studio 2013\Code Snippets\IntentV3\My Code Snippets

# Snippet Summary
* enc - Insert a call to en_Coalesce.
```
en_Coalesce(Foo, Bar)
```
* encl - Insert a set for rules for a uiProperty with choices.  User prompted for name and datatype.
```
Rule cl_Foo As List = {}
Parameter Rule dv_Foo As Number = First(cl_Foo)
Rule Foo As Number = uiFoo.value
Child uiFoo As :NumberProperty
End Child
```
* encr - Insert a call to en_Coalesce with the optional ruleName parameter.
```
en_Coalesce(Foo, Bar, ruleName:=:FooBar)
```
* enif - Insert an If statement.
```
en_Coalesce(Foo, Bar, ruleName:=:FooBar)
```
* enifelse - Insert an If-Else statement.

```
If (True) Then
	
Else

End If
```
* enll - Create a list of list rule.
```
Rule ruleName As List = { _
							{}, _
							{} _
							}
```
* enlook - Insert a lookup rule.
```
Lookup Rule Foo As Any = NoValue
```
* enover - Create a code region for overrides.
```
'==============================================================
'   Foo - Overrides
'==============================================================
```
* enparam - Insert a parameter rule.
```
Parameter Rule Foo As Any = NoValue
```
* enp - Insert a set for rules for a uiProperty.  User prompted for name and datatype.
```
Parameter Rule dv_Foo As String = NoValue
Rule Foo As String = uiFoo.value
Child uiFoo As :StringProperty
End Child
```
* enregion - Create a code region.
```
'==============================================================
'   Foo
'==============================================================
```
* enrule - Insert a rule.
```
Rule Foo As Any = NoValue
```

# License
MIT license - http://www.opensource.org/licenses/mit-license.php
