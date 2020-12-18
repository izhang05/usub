<div align="center">

# usub

[installation](##-installation) | [file submission](##-file-submission) | [submission status](##-submission-status) | [contributing](##-contributing)

</div>

## installation

``` sh
git clone https://github.com/mizlan/usub.git
cd usub
python -m venv venv
source venv/bin/activate # or source venv/bin/activate.fish
pip install -r requirements.txt
pip install -e .
```

## file submission

``` sh
usub 739 -f sol.cpp # using the cpid
# or
usub 'http://www.usaco.org/index.php?page=viewproblem2&cpid=739' -f cownomics.cpp
```

## submission status

``` sh
usub 739 -f cownomics.cpp # using the cpid
# or
usub 'http://www.usaco.org/index.php?page=viewproblem2&cpid=739' -f cownomics.cpp
```

## other options

From `usub -h`

```
usage: usub [-h] [--fresh] [--verbose] [-f FILE] [-l LANG] problem

USACO Submission Client

positional arguments:
  problem               USACO problem link or cpid

optional arguments:
  -h, --help            show this help message and exit
  --fresh               invalidate cookies and force fresh login
  --verbose             turn on verbose mode
  -f FILE, --file FILE  submission file
  -l LANG, --lang LANG  submission language
```

## contributing

please file issues, i'm open to PRs
