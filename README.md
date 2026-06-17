# ConcatCode

Concat all your code into one `.txt` file to do whatever you want with it
(paste into an LLM prompt, archive a snapshot, review a whole project at once...).

## What it does

`Concatcode.py` walks a project directory and concatenates the contents of
its source files into a single `.txt` file, with each file's path included
as a header, so you get one flat, greppable/pasteable document instead of
dozens of open tabs.

## Usage

```bash
python Concatcode.py <project_directory>
```

A standalone Windows build is also available via `ConcatCode.spec`
(PyInstaller), see the `dist/` folder for the packaged executable.
