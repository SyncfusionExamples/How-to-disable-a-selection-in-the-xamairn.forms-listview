# How to disable a selection in the xamairn.forms listview?
This example demonstrates how to disable a selection in the xamairn.forms listview by using the SelectionMode property.

## Sample

```xaml
<Grid>
    <syncfusion:SfListView x:Name="listView"
                            ItemSize="70"
                            SelectionMode="None"
                            ItemsSource="{Binding ContactsInfo}">
        <syncfusion:SfListView.ItemTemplate>
            <DataTemplate>
                <ViewCell>
                    <ViewCell.View>
                        <code>
                        . . .
                        . . .
                        <code>
                    </ViewCell.View>
                </ViewCell>
            </DataTemplate>
        </syncfusion:SfListView.ItemTemplate>
    </syncfusion:SfListView>
</Grid>
```

See [How to disable a selection in the xamairn.forms listview](https://www.syncfusion.com/kb/9982/how-to-disable-a-selection-in-the-xamairn-forms-listview) for more details.
## <a name="requirements-to-run-the-demo"></a>Requirements to run the demo ##

* [Visual Studio 2017](https://visualstudio.microsoft.com/downloads/) or [Visual Studio for Mac](https://visualstudio.microsoft.com/vs/mac/).
* Xamarin add-ons for Visual Studio (available via the Visual Studio installer).

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.