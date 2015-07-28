# ExpandableLayout 

A simple Expandable Layout, You can use it in ListView or RecyclerView like CheckBox.

![](https://github.com/KyoSherlock/ExpandableLayout/raw/master/screenshots/1.png)

![](http://d.picphotos.baidu.com/album/s=900;q=90/sign=3386d605a9c3793179688a29dbffc678/b3b7d0a20cf431ad8099573a4d36acaf2edd986d.jpg)

# Usage

Below is an example of a ExpandableLayout, what you need to do is just to set canExpand="true" to a child view.

    <com.sherlock.expandlayout.ExpandableLayout
        android:id="@+id/expandlayout"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="12dp" >

        <ImageView
            android:id="@+id/imageview"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:contentDescription="@null"
            android:scaleType="centerCrop"
            android:src="@drawable/parent" />

        <ImageView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="6dp"
            android:contentDescription="@null"
            android:scaleType="centerCrop"
            android:src="@drawable/child"
            app:canExpand="true" />
    </com.sherlock.expandlayout.ExpandableLayout>
