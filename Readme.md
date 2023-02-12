## Using poetry to manage virtual environment

### Check either poetry is installed

```bash
  poetry --version
```

### To start a new project with poetry

```
  poetry --init
```

### To add a package

```bash
  poetry add <package_name>
```

### To activate virtual env

```bash
  poetry shell
```

### To run the uvicorn server

```bash
  uvicorn main:app --reload
```
