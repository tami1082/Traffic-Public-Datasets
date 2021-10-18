This doc shows the detail of DCRNN.

Data has been processed and you can find the detail of the porecessed data in [Prepare_Data](https://github.com/tami1082/Traffic-Public-Datasets/blob/main/Prepare_Data.md).

**Encoder:**
Input X(time_seq,bacth_size, num_of_nodes, input_dim), e.g. (12,64,207,2)  
for each t into encoder_mode:  
x_t(64,207,2), hidden_state(num_of_layers, batch_size, hidden_state_size(nodes✖️rnn_units,207✖️64)), e.g. (2,64,13248) and in each layer, the hidden_state's dim is (64,13248).  
then, go into dcrnn_cell.py  
output_size = 2 * num_units = 128. In order to compute value, use -gconv, instead of multiplying.  
In gconv cell: the input's dim[2] (64,207,2) and the hidden_state's dim[2] (64,207,64) are concatenated, the final input's dim is (64,207,66(64+2)). There are some steps of reshaping matrixs.  
|x|(207,66,64)|(207,64,66)|(207,4224)|(1,207,4224)|(2,207,4224) concated|
|--|--|--|--|--|--|
|x0|(207,4224)✖️support(deep walk matrixs)(207,207)|(207,4224),concat with x|
|x1|
|x2|
