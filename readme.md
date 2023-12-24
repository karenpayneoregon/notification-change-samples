# About

When working with a DataGridView with a DataTable as the data source there is change notification built-in while when working with classes/models with controls a developer must implement INotifyPropertyChanged or use a third-party library like PostScript (a paid for library) or Fody.

This project shows conventional INotifyPropertyChanged and Fody for implementation of property change notification.

> **Note**
> That for controls such as ComboBox and ListBox where the underlying data may change, consider not using a DataTable but instead the same methods used for this code sample by replacing the DataGridView with a ComboBox or ListBox which works same as the DataGridView as the first iteration of this project used ListBox controls.


## Overview

Examples for conventional property change notification using [INotifyPropertyChanged](https://learn.microsoft.com/en-us/dotnet/api/system.componentmodel.inotifypropertychanged?view=net-8.0) and [PropertyChanged.Fody](https://www.nuget.org/packages/PropertyChanged.Fody/4.1.0?_src=template).

## See

Readme file in the project for more details.