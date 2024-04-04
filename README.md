# cmmd-pytorch

Modified cmmd-pytorch implementation to support CMMD calculation using `csv` files.

## Running

```bash
python main.py path_to_log_file header_for_original_images header_for_gen_images --batch_size=32 --max_count=30000
```

It should output:

```bash
The CMMD value is:  <some number>
```

## Acknowledgements
1. Sayak Paul for implementing CMMD in pytorch - [cmmd-pytorch](https://github.com/sayakpaul/cmmd-pytorch)

2. Google Research for original JAX implementation - [cmmd](https://github.com/google-research/google-research/tree/master/cmmd)
