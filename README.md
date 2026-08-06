# Lumen Development Repository

> 🚧 **Development Branch** - main development repository for Lumen

## About Lumen

Lumen runs analytics over labeled property graphs.

## 🔧 Development Status

This repository is under active development. Many features are TODO.

### 🔴 High Priority TODOs

- Core functionality is still being implemented across modules.

### 📝 Complete TODO List

- [ ] **lumen/algo/community.py:2** - add resolution parameter
- [ ] **lumen/algo/community.py:6** - break ties deterministically
- [ ] **lumen/algo/community.py:7** - cap iterations to avoid oscillation
- [ ] **lumen/algo/pagerank.py:2** - converge using L1 delta threshold
- [ ] **lumen/algo/pagerank.py:3** - support personalized pagerank vectors
- [ ] **lumen/store/adjacency.py:3** - use CSR layout for cache locality

## 🤝 Contributing

1. Pick a TODO item from the list above
2. Implement the functionality
3. Update this README when TODOs are completed
