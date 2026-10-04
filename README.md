# Meta-Retroduction
A machine that does meta-retroduction.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Meta-Retroduction!" \
  | uvx meta-retroduction \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install meta-retroduction
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
meta-retroduction -a multilogue.txt
```
Or:
```bash
meta-retroduction multilogue.txt > response.txt
```
Or:
```bash
meta-retroduction -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import meta_retroduction
```
