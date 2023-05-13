# Centering tkinter windows on screen


To center a tkinter window on the screen ...

```python
def center_screen(root, width, height):
    screen_width = root.winfo_screenwidth()
    screen_height = root.winfo_screenheight()
    x = (screen_width / 2) - (width / 2)
    y = (screen_height / 2) - (height / 2)
    return "%dx%d+%d+%d" % (width, height, x, y)
```




