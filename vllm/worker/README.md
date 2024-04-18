**CacheEngine.py**

> 负责管控KV Cache物理块。调度器中的Block Manager只负责物理块id的分配。
>
> * _allocate_kv_cache()
>
>   分配显存上的物理KV Cache

**worker.py**

> 负责
>
> * determine_num_available_blocks()
>
>   计算需要预分配的KV Cache

**model_runner.py**

> * 通过run一次假数据来计算KV Cache