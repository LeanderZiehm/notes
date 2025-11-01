
find . -type d -name "__pycache__" -print
find . -type d -name "__pycache__" -exec rm -r {} +
