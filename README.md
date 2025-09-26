# Project Title

## Quickstart
1. Train and save artifacts:
   python src/train.py

2. Run API locally:
   uvicorn src.app:app --reload --port 8000

3. Test:
   curl -X POST http://localhost:8000/predict -H "Content-Type: application/json" \
    -d '{"data": {"feature1": 1.2, "feature2": "X", "feature3": 10}}'
