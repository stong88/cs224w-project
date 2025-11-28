# CS224W Project

## Getting Started
1. Clone repo and pip install (`pip install -r requirements.txt`)! Recommended to use a Conda environment
2. Run `pre-commit install` to set up pre-commit hooks. In particular, we create a hook that removes ipynb output cells on git commit.

> In the event that the pre-commit hook outputs "failed" and `git commit` doesn't go through, it may be because the ipynb stripped output succeeded but wasn't staged with the rest of the commit (not sure why this happens...). In this case, simply `git add` the ipynb modification and re-commit.