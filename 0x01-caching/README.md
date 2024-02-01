# Caching System Project

This project implements various caching algorithms using Python classes. Each task is a separate Python file implementing a specific caching strategy.

## Tasks

### Task 0: Basic Dictionary Cache

**File:** `0-basic_cache.py`

- **Description:** Implements a basic caching system without a limit.
- **Class:** `BasicCache` (inherits from `BaseCaching`)
- **Methods:**
  - `put(self, key, item)`: Adds an item to the cache.
  - `get(self, key)`: Retrieves an item from the cache.

### Task 1: FIFO Caching

**File:** `1-fifo_cache.py`

- **Description:** Implements a caching system using the First-In-First-Out (FIFO) algorithm.
- **Class:** `FIFOCache` (inherits from `BaseCaching`)
- **Methods:**
  - `put(self, key, item)`: Adds an item to the cache using FIFO.
  - `get(self, key)`: Retrieves an item from the cache.

### Task 2: LIFO Caching

**File:** `2-lifo_cache.py`

- **Description:** Implements a caching system using the Last-In-First-Out (LIFO) algorithm.
- **Class:** `LIFOCache` (inherits from `BaseCaching`)
- **Methods:**
  - `put(self, key, item)`: Adds an item to the cache using LIFO.
  - `get(self, key)`: Retrieves an item from the cache.

### Task 3: LRU Caching

**File:** `3-lru_cache.py`

- **Description:** Implements a caching system using the Least Recently Used (LRU) algorithm.
- **Class:** `LRUCache` (inherits from `BaseCaching`)
- **Methods:**
  - `put(self, key, item)`: Adds an item to the cache using LRU.
  - `get(self, key)`: Retrieves an item from the cache.

### Task 4: MRU Caching

**File:** `4-mru_cache.py`

- **Description:** Implements a caching system using the Most Recently Used (MRU) algorithm.
- **Class:** `MRUCache` (inherits from `BaseCaching`)
- **Methods:**
  - `put(self, key, item)`: Adds an item to the cache using MRU.
  - `get(self, key)`: Retrieves an item from the cache.

### Task 5: LFU Caching

**File:** `100-lfu_cache.py`

- **Description:** Implements a caching system using the Least Frequently Used (LFU) algorithm.
- **Class:** `LFUCache` (inherits from `BaseCaching`)
- **Methods:**
  - `put(self, key, item)`: Adds an item to the cache using LFU.
  - `get(self, key)`: Retrieves an item from the cache.
