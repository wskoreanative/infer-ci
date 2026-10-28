
---
title: Installation
---

# 🛠 Installation

## 1. 📥 Download or Clone the Repository

> **Tip:** Skip this step if you plan to install the package directly from PyPI or GitHub.

### 1.1. Create the projects directory

```sh
mkdir -pv ~/workspaces/projects
cd ~/workspaces/projects
```

### 1.2. Choose one of the following options

**Option A: Clone the repository**

```sh
git clone https://github.com/humblebeeai/infer-ci.git
cd infer-ci
```

**Option B: Clone using SSH (for development)**

```sh
git clone git@github.com:humblebeeai/infer-ci.git
cd infer-ci
```

**Option C: Download the source code**

1. Download the ZIP file from the [GitHub Releases](https://github.com/humblebeeai/infer-ci/releases) page.
2. Extract the archive into the projects directory.

## 2. 📦 Install the Package

Choose one of the following installation methods.

**Option A: Install from PyPI (Recommended)**

```sh
pip install -U infer-ci
```

**Option B: Install directly from GitHub**

```sh
pip install git+https://github.com/humblebeeai/infer-ci.git
```

**Option C: Install from source**

```sh
pip install .
```

For editable installation:

```sh
pip install -e .
```

**Option D: Install for development**

```sh
pip install -e ".[dev]"
pre-commit install
```

**Option E: Install from a release package**

1. Download a `.whl` or `.tar.gz` file from the [GitHub Releases](https://github.com/humblebeeai/infer-ci/releases) page.
2. Install the downloaded file:

```sh
pip install ./infer-ci-[VERSION]-py3-none-any.whl
```

Or:

```sh
pip install ./infer-ci-[VERSION].tar.gz
```

**Option F: Copy the module into your project (for testing)**

```sh
pip install -r ./requirements.txt
cp -r ./src/infer-ci [PROJECT_DIR]
```
