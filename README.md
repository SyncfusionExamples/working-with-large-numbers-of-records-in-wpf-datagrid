# WPF DataGrid - Working with large numbers of records
Example shows the built-in data virtualization support in WPF DataGrid where it processes the record creations in on-demand for better loading performance. 

In this way, datagrid provides the same loading time for 1K records and 1 million record. You can enable data virtualization in datagrid by setting [EnableDataVirtualization](https://help.syncfusion.com/cr/cref_files/wpf/Syncfusion.SfGrid.WPF~Syncfusion.UI.Xaml.Grid.SfDataGrid~EnableDataVirtualization.html) property. Also, setting [UseDrawing](https://help.syncfusion.com/cr/cref_files/wpf/Syncfusion.SfGrid.WPF~Syncfusion.UI.Xaml.Grid.SfDataGrid~UseDrawing.html) property as `Default` improves the loading and also scrolling performance.

In addition to that datagrid provides option to show built-in busy indicator for long running operations by setting [ShowbusyIndicator](https://help.syncfusion.com/cr/cref_files/wpf/Syncfusion.SfGrid.WPF~Syncfusion.UI.Xaml.Grid.SfDataGrid~ShowBusyIndicator.html) as `true` to enhance the user experience.

## Reference

[WPF DataGrid Performance](https://help.syncfusion.com/wpf/sfdatagrid/performance)

[WPF DataGrid](https://www.syncfusion.com/products/wpf-ui-controls/datagrid)

## Other examples

[WPF DataGrid - Scrolling performance with more number of rows and columns example](https://github.com/SyncfusionExamples/wpf-datagrid-scrolling-performance-with-more-rows-and-columns)

[WPF DataGrid Performance - Asynchronous scrolling example](https://github.com/SyncfusionExamples/wpf-datagrid-asynchronous-scrolling)
