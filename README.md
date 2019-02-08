Software Heritage CI environment
========================================

Add the .mrconfig to your .mrtrust file:

```
echo $CI_ENVIRONMENT/.mrconfig >> ~/.mrtrust
```

Then update your environment:

```
git pull && mr update
```
