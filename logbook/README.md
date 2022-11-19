# Distributed Training

**Logs** -

- ``` nvidia-smi --query-gpu=timestamp,name,pci.bus_id,driver_version,pstate,pcie.link.gen.max,pcie.link.gen.current,temperature.gpu,utilization.gpu,utilization.memory,memory.total,memory.free,memory.used --format=csv -l 1 > results-file.csv ```

- Highest Batch size -> 256

- Tensorboard Link -> https://tensorboard.dev/experiment/l1LXCpzYSw2EKCdVY7A8Ag/#scalars

- GPU Usage - results-file.csv

- Thoroughly commented - you can use this repo as a reference and educational resource.

