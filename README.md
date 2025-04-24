# VTEXS-666
- 提供开箱即用的AI模型部署解决方案，支持PyTorch/TensorFlow模型一键API化 - 内置模型监控、版本管理和自动扩缩容功能
# AIModelDeployKit

[![CI](https://github.com/l234567777777/AIModelDeployKit/actions/workflows/ci.yml/badge.svg)](https://github.com/l234567777777/AIModelDeployKit/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 快速开始
```bash
# 启动开发服务器
docker-compose up -d

# 测试API端点
curl -X POST http://localhost:8000/predict \
  -H "Content-Type: application/json" \
  -d '{"input": "sample_data"}'
