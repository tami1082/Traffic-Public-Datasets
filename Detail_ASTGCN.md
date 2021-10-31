This is a doc that explains the model of [ASTGCN](https://github.com/guoshnBJTU/ASTGCN-r-pytorch).  
Data has been processed and you can find the detail of the porecessed data in [Prepare_Data](https://github.com/tami1082/Traffic-Public-Datasets/blob/main/Prepare_Data.md).

* Prepare: Data, chevb coefficients, model.

See the detail data in the pics, from left to right, x-train/x-val/x-test/  
<p align="left">
  <img src="Images/astgcn/带有全部特征的x-train.png" width="324" height="153" />  
  <img src="Images/astgcn/带有全部特征的x-val.png" width="324" height="153" />  
  <img src="Images/astgcn/带有全部特征的x-test.png" width="324" height="153" />  
</p>

After that, adj_matrix is loaded. 
<p align="middle">
  <img src="Images/astgcn/adj_distant2.png" width="1139" height="216" />  
</p>

The coefficients of chevb.
<p align="middle">
  <img src="Images/astgcn/chev多项式的多项式.png" width="903" height="188" />  
</p>

The whole model.  
<p align="middle">
  <img src="Images/astgcn/whole model.png" width="1003" height="710" />  
</p>
