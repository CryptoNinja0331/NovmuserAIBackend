<div align="center">

# **Novmuser AI Backend**

**The backend of Novmuser AI**

</div>

## Table of contents

- [Setting up environemnt](#setting-up-environemnt)
  - [Install poetry](#1-install-poetry)
  - [Install dependencies](#2-install-dependencies)
  - [Virtual-env](#3-virtual-env)
- [Get started](#get-started)
  - [Launch fastapi](#1-launch-fastapi)

## Setting up environemnt

### 1. Install poetry

Reference: https://python-poetry.org/

### 2. Install dependencies

```bash
poetry install --no-root
```

### 3. Virtual Env

```bashv
poetry shell
```

## Get started

<span style="color:red">:warning: Insurance that already enter into virtual env before launching</span>.

### 1. Launch fastapi

```bash
python -m uvicorn main:app
```
