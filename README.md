# Python Github Action

Convert Jupyter Notebooks to Databricks Notebooks

## Sample Usage

```yaml
name: lint

on: push
jobs:
  lint:
    runs-on: ubuntu-latest
    steps:
    - name: Convert Jupyter Notebooks to Databricks Notebooks
      uses: rafaelvp-db/jupyter-to-databricks@v1.1
      with:
        inputPath: example/jupyter
        outputPath: example/databricks

```
