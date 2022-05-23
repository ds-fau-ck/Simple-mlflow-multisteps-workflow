# Simple-mlflow-multisteps-workflow

## commands -
* simple workflow execution 'with' new conda enviriónment 
```bash 
mlflow run .
```
* simple workflow execution 'without' new conda enviriónment 
```bash 
mlflow run . --no-conda
```
* simple workflow execution 'without' new conda enviriónment with parameters
```bash 
mlflow run . -P param-value --no-conda
```
* run only on entry point
```bash 
mlflow run . -e entry_point_name --no-conda
```