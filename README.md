# MLOps Task

## Run locally
python run.py --input data.csv --config config.yaml --output metrics.json --log-file run.log

## Run with Docker
docker build -t mlops-task .
docker run --rm mlops-task

## Output
metrics.json contains signal_rate and latency
---

## 🚀 How it works (Pipeline Flow)
1. Input data is read from `data.csv`
2. Configuration is loaded from `config.yaml`
3. Processing is executed via `run.py`
4. Metrics are generated and saved in `metrics.json`
5. Logs are stored in `run.log`

---

## 🛠️ Tech Stack
- Python
- Docker
- YAML Configuration
- JSON Output
