# Open3DStream

A comprehensive framework for streaming 3D data with Open3D integration, supporting real-time point cloud and mesh streaming.

## Overview
Open3DStream provides a robust implementation for streaming 3D data using Open3D, enabling real-time transmission and processing of point clouds, meshes, and other 3D data formats.

## Features
- Real-time 3D data streaming
- Point cloud processing
- Mesh streaming support
- Python and C++ APIs
- Plugin architecture
- Documentation generation

## Project Structure
```
├── apps/         # Applications
├── src/          # Core C++ implementation
├── python/       # Python bindings
├── plugins/      # Plugin system
├── sphinx/       # Documentation
├── test_data/    # Test assets
└── thirdparty/   # Dependencies
```

## Building

### Prerequisites
- CMake
- C++ compiler
- Python 3.x
- Open3D dependencies

### Build Steps
```bash
# Windows
./build_env.bat
./build.bat

# Unix
make
```

## Documentation
Generate documentation:
```bash
./build_doc.bat
```

## Development
- Clang format configuration provided
- CMake build system
- Comprehensive test data
- Plugin development support

## Python Usage
```python
import open3dstream as o3s

stream = o3s.Stream()
stream.connect()
```

## C++ Usage
```cpp
#include <open3dstream/stream.h>

auto stream = open3dstream::Stream();
stream.connect();
```

## Testing
Test data available in `test_data/` directory for:
- Point cloud streaming
- Mesh processing
- Protocol validation 