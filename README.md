# WEEK1 University API

A simple application to retrieve student data by student id.

## Install

```
python -m pip install -r requirements.txt
```

## Run
```
uvicorn main:app --reload
```
## Endpoints

| Method | Path | Description |
| --- | --- | --- |
| GET | `/` | API name, version, endpoints summary |
| GET | `/students/` | All student data |
| GET | `/students/{student_id}` | Student data matching the student id |