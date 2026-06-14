HLD Interview Answer

For a high-traffic service:

Browser Cache
      ↓
CDN
      ↓
Load Balancer
      ↓
Application Local Cache (RAM)
      ↓
Redis
      ↓
Database


| Storage         | Latency   |
| --------------- | --------- |
| L1 Cache        | ~1 ns     |
| L2 Cache        | ~4 ns     |
| L3 Cache        | ~10-20 ns |
| RAM             | ~100 ns   |
| Redis (network) | ~0.1-1 ms |
| Database        | ~1-100 ms |


l1, l2, l3 and ram are more like system cache (just google or ask gpt for instant clarification)