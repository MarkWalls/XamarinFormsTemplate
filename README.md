# XamarinFormsTemplate
Source code of Xamarin.Forms Template
This is NOT a source code of vsix. 
Please see [this entry (in Japanese)](http://ytabuchi.hatenablog.com/entry/vs-xf-template) for how to use.

# How to maintenance

`MyTemplate.vstemplate` located in Root folder is a Master file that is specify each child projects.
In each projects folder, there are `MyTemplate.vstemplate` files. They are the template setting files for each projects.

If Xamarin.Forms will be updated, you can just change the version numbers of each `MyTemplate.vstemplate` files

There are some macros in the template files. Please see [MSDN document](https://msdn.microsoft.com/ja-jp/library/eehb4faa.aspx) for each meaning.
