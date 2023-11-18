
https://kdiff3.sourceforge.net/

Merge tool
```
git config --global merge.tool kdiff3
git config --global mergetool.kdiff3.path "C:/Program Files/KDiff3/kdiff3.exe"
git config --global mergetool.kdiff3.trustExitCode false
```

Diff tool
```
git config --global diff.guitool kdiff3
git config --global difftool.kdiff3.path "C:/Program Files/KDiff3/kdiff3.exe"
git config --global difftool.kdiff3.trustExitCode false
```

Open mergetool
```
git mergetool
```
