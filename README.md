# Projects

Data Engineering portfolio focused on building practical systems for real-time data ingestion, streaming, storage, and processing.

## Data Engineering Projects

### 01 — Binance WebSocket Client

Real-time cryptocurrency market data monitor built with Python, asyncio, WebSockets, and Textual.

**Technologies:** Python · asyncio · WebSockets · Binance WebSocket API · Textual

**Key features:**
- Real-time Binance 1-second OHLCV market data
- Dynamic WebSocket subscriptions and unsubscriptions
- Automatic reconnection and subscription restoration
- Heartbeat monitoring
- Interactive terminal user interface
- Connection and subscription status monitoring

[View Project](https://github.com/mahmoud8999/binance-websocket-client)

---

### 02 — Binance Market TUI
Real-time cryptocurrency market monitoring application built with Python,
Binance WebSockets, Textual, asyncio, and Docker.

**Technologies:** Python · asyncio · WebSockets · Binance WebSocket API · Textual · Docker · Linux

**Key Features:**
- Object-oriented WebSocket client
- Real-time market data streaming
- Dynamic stream subscriptions
- Interactive Textual TUI
- Docker containerization
- VPS deployment

[View Project](https://github.com/mahmoud8999/binance-market-tui)

--- 

### 03 — GTFS Realtime Pipeline

Real-time data ingestion and streaming pipeline that retrieves railway vehicle-position data from Malaysia's GTFS Realtime API, processes Protocol Buffers messages, and publishes normalized records to Apache Kafka using Redpanda.

**Technologies:** Python · REST API · Protocol Buffers · Apache Kafka · Redpanda · Docker · ThreadPoolExecutor · JSON

**Key Features:**
- Real-time railway vehicle-position data ingestion from a REST API
- GTFS Realtime Protocol Buffers decoding and data normalization
- Kafka producer and consumer implementation using Confluent Kafka
- Redpanda message broker deployed with Docker Compose
- Change detection to prevent publishing identical API responses
- Concurrent producer and consumer execution using Python threads
- Kafka message serialization and deserialization using JSON
- Graceful shutdown and error handling

[View Project](https://github.com/mahmoud8999/gtfs-realtime-pipeline)

--- 

### 04 — Binance Parquet & DuckDB Analytics

Historical cryptocurrency market data ingestion and analytics pipeline built with Python, Binance REST API, PyArrow, Apache Parquet, and DuckDB.

**Technologies:** Python · REST API · Requests · PyArrow · Apache Parquet · DuckDB · SQL

**Key Features:**
- Historical hourly OHLCV market data ingestion from Binance REST API
- Multi-symbol data retrieval with API pagination
- Batch-based data processing using PyArrow
- Schema definition and columnar data transformation
- RecordBatch and RecordBatchReader implementation
- Efficient historical market data storage using Apache Parquet
- SQL analytics directly on Parquet files using DuckDB
- Historical data validation and missing candle detection using SQL window functions

[View Project](https://github.com/mahmoud8999/binance-parquet-duckdb)

---

### More Projects Coming Soon

This portfolio is continuously evolving, with upcoming projects exploring advanced data engineering technologies, scalable data pipelines, distributed processing, and analytical systems.
