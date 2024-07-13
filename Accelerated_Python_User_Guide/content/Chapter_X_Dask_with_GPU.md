# Chapter X: Dask with GPUs




## Setting up a Local Cluster


```Python
from dask.distributed import LocalCluster
cluster = LocalCluster()
client = cluster.get_client()
```


```Python
from dask_cuda import LocalCUDACluster
cluster = LocalCUDACluster()
client = cluster.get_client()
```

