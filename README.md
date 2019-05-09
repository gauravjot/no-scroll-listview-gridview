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
All general attributes of ListView and GridView can be used.
