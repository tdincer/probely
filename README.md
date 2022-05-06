# Probely

Single Probe Design with Emitters

```python
from probely import Probe

# Create design
P = Probe(
    probe_dimensions=[1200, 120, 1300],
    n_e_box=[5, 60],
    e_box_length=10,
    e_box_sep=10,
    e_box_vertical_margin=5,
    e_box_horizontal_margin=15,
    n_d_box=[0, 0],
    d_box_length=0,
    d_box_sep=0,
    d_box_vertical_margin=0,
    d_box_horizontal_margin=0,
    name="P1",
)
```

To plot the probe in 2D:

```python
P.plot_2d(show=True)
```

![Single Probe with emitters](images/SingleProbeemitteronly.png)


# Installation
```
pip install probely
```