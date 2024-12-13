# Sentimental Adjective-based Instruction Instance

The repo contains the constructed instruction instance using the method proposed in section 2.2 in the paper. 

 - `train_sample_for_negative.json` contains instances for negative class
 - `train_sample_for_positive.json` contains instances for positive class
 - `train_sample_for_neutral.json` contains instances for neutral class

Please download all .json files into YOUR_LOCAL_DIRECTORY. To load `.json` file:

```python
def read(path):
    import json
    with open('path_to_your_file.json', 'r') as file:
        data = json.load(file)

data_negative = read('train_sample_for_negative.json')
```
