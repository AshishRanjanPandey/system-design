# 🗄️ Database Sharding

Sharding is a technique of splitting a large database into smaller parts called shards.

## Architecture

Application
     |
     v
 Query Router
  /     |     \
Shard1 Shard2 Shard3

## Benefits

- Horizontal scaling
- Faster queries
- Reduced database load
