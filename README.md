## Overview

REST API for thenewboston.com.

## Project Setup

Follow the steps below to set up the project on your environment. If you run into any problems, feel free to leave a 
GitHub Issue or reach out to any of our communities above.

Install required packages:
```
pip3 install -r requirements/local.txt
```

## Developers

When adding a package, add to `requirements/base.in` and then:
```
bash scripts/compile_requirements.sh
```

To run tests:
```
pytest
```

To check styling:
```
flake8 --config=.flake8 config tests v1
```

## Community

Join the community to stay updated on the most recent developments, project roadmaps, and random discussions about 
completely unrelated topics.

- [thenewboston.com](https://thenewboston.com/)
- [Slack](https://join.slack.com/t/thenewboston/shared_invite/zt-j7j4ie92-ADy7GL3KAzCwSlaAVoDKLw)
- [reddit](https://www.reddit.com/r/thenewboston/)
- [LinkedIn](https://www.linkedin.com/company/thenewboston-developers/)
- [Facebook](https://www.facebook.com/TheNewBoston-464114846956315/)
- [Twitter](https://twitter.com/bucky_roberts)
- [YouTube](https://www.youtube.com/user/thenewboston)

## Donate

All donations will go to thenewboston to help fund the team to continue to develop the community and create new content.

| Coin | Address |
|-|-|
| ![thenewboston Logo](https://github.com/thenewboston-developers/Website/raw/development/src/assets/images/thenewboston.png) | b6e21072b6ba2eae6f78bc3ade17f6a561fa4582d5494a5120617f2027d38797 |
| ![Bitcoin Logo](https://github.com/thenewboston-developers/Website/raw/development/src/assets/images/bitcoin.png) | 3GZYi3w3BXQfyb868K2phHjrS4i8LooaHh |
| ![Ethereum Logo](https://github.com/thenewboston-developers/Website/raw/development/src/assets/images/ethereum.png) | 0x0E38e2a838F0B20872E5Ff55c82c2EE7509e6d4A |

## License

thenewboston is [MIT licensed](http://opensource.org/licenses/MIT).
