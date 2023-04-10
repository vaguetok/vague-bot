# vague-bot
Our Discord bot


---
## Contributing

### Set up your local environment
If you want to sandbox this integration to a virtual environment, please set that up before starting this section.


#### Install dependencies
```bash
pip3 install -r requirements.txt -r dev-requirements.txt
```

#### Enable pre-commit hooks
These checks ensure that the code we merge in conforms to an opinionated style.
Running this `install` ensures that the checks will be run before your code
is pushed up to github.

```bash
pre-commit install --hook-type pre-push
```

If you ever want to run the checks ad-hoc, you can run `pre-commit run --all-files`.

