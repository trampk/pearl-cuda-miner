PCM miner

CUDA miner for Pearl blockchain

https://t.me/+hu2FqT-zz2ExODA6



<details>
<summary><strong>HiveOs Flight Sheet</strong></summary>

<div align="left">
<img src="https://github.com/user-attachments/assets/78356d9a-edf4-4ec0-834a-6227304884f5" alt="PCM miner HiveOS flight sheet" width="50%" />
</div>

```json
{
  "name": "PCM miner 0.0.2y",
  "isFavorite": false,
  "items": [
    {
      "coin": "PEARL",
      "pool_ssl": false,
      "wal_id": 11040229,
      "dpool_ssl": false,
      "miner": "custom",
      "miner_alt": "pcm-miner",
      "miner_config": {
        "url": "stratum+tcp://prl-eu.kryptex.network:7048",
        "algo": "pearlhash",
        "miner": "pcm-miner",
        "template": "%WAL%.%WORKER_NAME%",
        "install_url": "https://github.com/trampk/pearl-cuda-miner/releases/download/v0.0.2y/pcm-miner-0.0.2y.tar.gz"
      },
      "pool_geo": []
    }
  ]
}
```

</details>

press S to switch to extended statistics

OC 

--cclk --coff --mclk --moff --pl --fan

example --cclk 1430 --coff 255 --mclk 810 --moff 0 --pl 120 --fan 60

GPU Selection

--gpus 0,1,2,3,4,5 etc.

Autotune

--uv (standart tune ~30-60 min)

--uv-hard (hard tune ~30-90 min average)

--uv-reset (tune reset)


--uv 0,2,3 for selected gpu

--uv-hard 0,2,3 for selected gpu

--uv-reset 0,2,3 (tune reset for selected gpu)
