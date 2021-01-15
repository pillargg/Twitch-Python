# Contributing

## Community

This project is intended for use by Pillar, for our own internal use of the Twitch API. The `master` branch is for our [own deployment](https://pypi.org/project/pillar-twitch-python) of the Twitch-Python wrapper. If you wish to contribute to this project, consider forking the [original Twitch-Python](https://github.com/PetterKraabol/Twitch-Python) by [Petter Kraabøl](https://github.com/PetterKraabol) and making a PR to his repo. Unless explicitly needed by Pillar, all pull requests to the `master` branch that are not made by Pillar employees will be closed and will not be merged. We will periodically update the `master` and `upstream` branches to match any features that are implemented on the `master` branch of Twitch-Python. 

## Employees and Partners

If there is a new feature that a Pillar employee needs to implement, please create a new branch using the branch `upstream` as a base and make a PR back to the branch `upstream` before then making a PR to the `master` branch. This ensures we can also make a PR on the original Twitch-Python repo without adding extra files and changes not wanted on the original project.