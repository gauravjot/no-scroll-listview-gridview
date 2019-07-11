## no-scroll-listview-griview for Android Development

Using these library files will remove the scrolling effect of `ListView` and `GridView`. You can then use these within `ScrollView` or MergeAdapters (CWAC) and it should work natively with the scroller provided by those views.

Simply add .java files to your project and intialize them as following:

```
NoScrollListView noScrollListView = findViewById(R.id.noScrollListView);
NoScrollGridView noScrollGridView = findViewById(R.id.noScrollGridView);
```

In XML files:
```
<com.domain.project.NoScrollListView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
/>
  
<com.domain.project.NoScrollGridView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
/>
```  

Example with `ScrollView`:
```
<ScrollView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content">
    
    <com.domain.project.NoScrollListView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
    />
    
</ScrollView>
```

All general attributes of ListView and GridView can be used.
