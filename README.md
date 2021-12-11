# ViewModelBase Class for WPF
This class can be used as parent class for MVVM in WPF.

## Example of ViewModel class is:
```c#
public class MyViewModel : ViewModelBase
{
    private int myProperty;
    public int MyProperty
    {
        get { return myProperty; }
        set { SetProperty(ref myProperty, value);
    }
}
```

For ease of writing, the [snippet file](https://github.com/rastegari-mrr/wpf-viewmodelbase/blob/main/ViewModelBase.xml) can be used. See the [Microsoft Code snippets page](https://docs.microsoft.com/en-us/visualstudio/ide/code-snippets?view=vs-2019) for more information.
