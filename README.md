# INSTALL
```
!pip install git+https://github.com/HazemElmahy/GNN_CARE.git
```

# IMPORT 
```
from GNN_CARE.model import OneLayerCARE
from GNN_CARE.utils import load_data, normalize, sparse_to_adjlist, pos_neg_split, undersample, test_sage, test_care
from GNN_CARE.graphsage import GraphSage, MeanAggregator, Encoder
from GNN_CARE.layers import InterAgg, IntraAgg, RLModule, filter_neighs_ada_threshold, mean_inter_agg, weight_inter_agg, att_inter_agg, threshold_inter_agg
```
