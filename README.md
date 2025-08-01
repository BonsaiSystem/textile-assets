# Textile Assets

This repository contains runtime assets for the Textile desktop application:

- **AI Models**: LLM models and embeddings for text processing
- **Platform Binaries**: Qdrant vector database and Llama.cpp server binaries
- **Configuration**: BM25 search configurations and tokenizers

## Assets by Platform

### Models (Universal)
- `Qwen3-1.7B-Q5_K_M.gguf` - Large Language Model (1.2GB)
- `potion-base-8M.tar.gz` - Embedding model (56MB)
- `bm25.tar.gz` - BM25 search configurations (34KB)

### Binaries by Platform

#### Linux
- `qdrant-x86_64-unknown-linux-gnu.tar.gz` - Qdrant vector database
- `llama-ubuntu-x64.tar.gz` - Llama.cpp server (CPU)
- `llama-ubuntu-vulkan-x64.tar.gz` - Llama.cpp server (Vulkan GPU)

#### macOS
- `qdrant-aarch64-apple-darwin.tar.gz` - Qdrant (Apple Silicon)
- `qdrant-x86_64-apple-darwin.tar.gz` - Qdrant (Intel)
- `llama-macos-arm64.tar.gz` - Llama.cpp (Apple Silicon)
- `llama-macos-x64.tar.gz` - Llama.cpp (Intel)

#### Windows
- `qdrant-x86_64-pc-windows-msvc.tar.gz` - Qdrant vector database
- `llama-win-cpu-x64.tar.gz` - Llama.cpp (CPU)
- `llama-win-cuda-12.4-x64.tar.gz` - Llama.cpp (CUDA GPU)
- `llama-win-vulkan-x64.tar.gz` - Llama.cpp (Vulkan GPU)
- Additional variants for different hardware configurations

## Usage

These assets are automatically downloaded by the Textile desktop application during first-time setup. They are hosted publicly for easy access without authentication requirements.

Total download size varies by platform (typically 1.3-1.5GB including the LLM model).