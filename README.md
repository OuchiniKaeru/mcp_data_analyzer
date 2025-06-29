# MCP Data Analizer

## Features

*   **Data Loading and Analysis**: Supports loading `.xlsx` and `.csv` files for statistical analysis.
*   **Visualization**: Generate various graphs and charts using `matplotlib` and `plotly`.

## Installation

To install this project, clone the repository using git:

```bash
git clone https://github.com/OuchiniKaeru/mcp_data_analyzer.git
cd mcp_data_analyzer
uv sync
```

### Development (Unpublished Servers)
```json
"mcpServers": {
  "mcp-data-analizer": {
    "command": "uv",
    "args": [
      "--directory",
      "/path_to_mcp_data_analizer/src/mcp_data_analizer",
      "run",
      "mcp_data_analizer"
    ]
  }
}
```

### Published Servers
```json
"mcpServers": {
  "mcp-data-analizer": {
    "command": "uvx",
    "args": [
      "mcp_data_analizer"
    ]
  }
}
```

## 機能

*   **データ読み込みと分析**: `.xlsx` および `.csv` ファイルの読み込みと統計分析をサポートします。
*   **可視化**: `matplotlib` および `plotly` を使用して、さまざまなグラフやチャートを生成します。

## インストール

このプロジェクトをインストールするには、git を使用してリポジトリをクローンします。

```bash
git clone https://github.com/OuchiniKaeru/mcp_data_analyzer.git
cd mcp_data_analyzer
uv sync
```

### 開発 (未公開サーバー)
```json
"mcpServers": {
  "mcp-data-analizer": {
    "command": "uv",
    "args": [
      "--directory",
      "/path_to_mcp_data_analizer/src/mcp_data_analizer",
      "run",
      "mcp_data_analizer"
    ]
  }
}
```

### 公開サーバー
```json
"mcpServers": {
  "mcp-data-analizer": {
    "command": "uvx",
    "args": [
      "mcp_data_analizer"
    ]
  }
}
```
