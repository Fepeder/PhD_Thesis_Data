# Description

The structure of the instance is the following: 
- Number of SKU | Type: number
- Name of SKU | Type: text
- Number of BIN | Type: number
- Number of Times | Type: number
- Initial Stock for each SKU | Type: number
- Production expected for each SKU | Type: number
- Outbound expected for each SKU | Type: number
- Matrix Capacity Sku x BINS | Type: matrix numbers 7rows x 23 columns

# NB:
The structure of the instance is missing the cost to assign SKU $i$ to bin $j$, $A_{ij}$.
Since the company is using the same cost for each bin and SKU, it is based on having $A_{ij}=1$, for all $i$ and $j$.
For convenience, this cost has been inserted directly into the model code. 


[🔙](https://github.com/Fepeder/PhD_Thesis_Data/tree/main/Chapter%201/)
