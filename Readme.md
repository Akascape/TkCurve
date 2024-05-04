# TkCurve
A curve widget editor for tkinter, can be used in complex programs for better controls.

![image](https://github.com/Akascape/TkCurve/assets/89206401/b4cd7314-b899-4244-b4ee-1ff25355ba7c)

## Usage
```python
import tkinter as tk
from tkcurve import CurveWidget

root = tk.Tk()
root.config(bg="black")

values = [(300,0), (150,150), (0,300)]
curve_widget = CurveWidget(root, values, line_color="purple",
                           point_color="white", outline="black")
curve_widget.pack(side="left", padx=10, pady=10)

values2 = [(300,0), (150,150), (0,300)]
curve_widget2 = CurveWidget(root, values2)
curve_widget2.pack(side="left", padx=10, pady=10)

values3 = [(300,0), (200,200), (75, 75), (0,300)]
curve_widget3 = CurveWidget(root, values3, line_color="green")
curve_widget3.pack(side="left", padx=10, pady=10)

root.mainloop()
```

## Parameters

## Methods
