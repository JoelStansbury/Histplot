# Histplot
An efficient scatterplot alternative for large datasets

#### What's wrong with a scatterplot?
* It takes a very long time (<span style="color:red">38.8 seconds</span> in this case) to produce a ~1Million point graph using matplotlib.pyplot
* Points overlap and hide those underneath

#### How is this different?
* Labels are assigned a RGB color
* A 2D histogram is created for each label
* RGB matricies for all labels are combined and normalized to produce a single RGB image
* Much faster (0.4 seconds)
* <span style="color:Green">No obstruction</span>
* <span style="color:red">Can be difficult to see edge cases</span>

> More info can be found in the .ipnb file

<table align="left">
  <tr>
    <td style="text-align:center">Scatter</td>
    <td style="text-align:center">Hist</td>
    <td style="text-align:center">Hist (with gain) </td>
  </tr>
  <tr>
    <td><img src='scatter.png'  style="width:220px;height:200px;"></td>
    <td><img src='hist2.png' style="width:200px;height:200px;"></td>
    <td><img src='hist.png' style="width:200px;height:200px;"></td>
  </tr>
</table>



