**scheduler.py**

> 调度器，分配物理块的id。
>
> 在CPU中运行。
>
> * _passed_delay：判断在waiting队列中调度
> * can_allocate：
>
> 具体的抢占逻辑在这里！

**interfaces.py**

>  

**block_manager.py**

> 管理着BlockAllocator（实际参与分配物理块）
>
> 但只负责分配id
>
> * can_allocate

---

block文件夹内:

**cpu_gpu_block_allocator.py**

**interfaces.py**

> 实际参与分配物理块的类。



