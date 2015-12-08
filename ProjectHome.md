# Description #

A simple file browsing component for ExtJS.

**Note**:
The download contains a php backend. This is written as a sample to make it work out of the box. However, it is by no means safe to implement in a production environment.

# Example Usage #
To show the filebrowserpanel in a specified div,
simply create a new instance and render it to the div as a normal panel.
So say you have a div with id 'filebrowser-ct', you can do:
```
var fb = new Ext.ux.FileBrowserPanel({
    width: 800,
    height: 600,
    renderTo: 'filebrowser-ct'
});
```

or in a window:
```
var win = new Ext.Window({
  title: 'FileBrowser',
  layout: 'fit',
  width: 800,
  height: 600,
  items: [{
    xtype: 'ux-filebrowserpanel'
  }]
});

win.show();
```

# Screenshots #
<a href='http://s879.photobucket.com/albums/ab353/bruijn88/?action=view&current=screenshot-grid.png'><img src='http://i879.photobucket.com/albums/ab353/bruijn88/th_screenshot-grid.png' alt='screenshot grid' border='0' /> </a>

<a href='http://s879.photobucket.com/albums/ab353/bruijn88/?action=view&current=screenshot-thumbnails.png'><img src='http://i879.photobucket.com/albums/ab353/bruijn88/th_screenshot-thumbnails.png' alt='screenshot thumbnails' border='0' /> </a>



See 'docs' folder for more information