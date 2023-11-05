# Install packages in Jupyter

When you hit the error:

```
ModuleNotFoundError: No module named 'google.generativeai'
```

Run:

```python
!pip install <package-name>
```


For older version, you might need to run:

```python
import sys
!{sys.executable} -m pip install <package-name>
```


To suppress the installation message, add `-qqq`:

```python
!{sys.executable} -m pip install -qqq google-generativeai
```
