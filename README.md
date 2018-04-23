# MXNet the Straight Dope

Source code as I work through the [MXNET The Straight Dope book][official-repository].

Install dependencies with [pipenv][pipenv-github].

```sh
python3 -m pipenv install
```

Test the [MXNet][mxnet-official] installation with one of the following commands.

```sh
python3 -m pipenv run python3 -c "import mxnet as mx; print((mx.nd.ones((3,2))*3+0.5).asnumpy())"
./python.sh -c "import mxnet as mx; print((mx.nd.ones((3,2))*3+0.5).asnumpy())"
```

The following output should be displayed.

```sh
[[3.5 3.5]
 [3.5 3.5]
 [3.5 3.5]]
```

# References / External Links

- [Machine Learing, Google's AI is Now Smart Enough to Play Atari Like the Pros](https://www.wired.com/2015/02/google-ai-plays-atari-like-pros/)
- [Machine Learing, Google's AlphaGo Trounces Humans- But it Also Gives Them a Boost](https://www.wired.com/2017/05/googles-alphago-trounces-humans-also-gives-boost/)
- [MXNet, Apache MXNet Home Page][mxnet-official]
- [MXNet, Build from Source][mxnet-build]
- [MXNet, Deep Learning - The Straight Dope, Official Repository][official-repository]
- [MXNet, Gluon Home Page](https://mxnet.apache.org/gluon/index.html)
- [MXNet, Tutorial Slides](https://github.com/zackchase/mxnet-slides)
- [Python, Jupyter Documentation](http://jupyter.readthedocs.io/en/latest/index.html)
- [Python, Jupyter Home Page](http://jupyter.org)
- [Python, Pipenv Documentation](http://pipenv.readthedocs.io/en/latest/)
- [Python, Pipenv GitHub Repository][pipenv-github]

[mxnet-build]: http://mxnet.incubator.apache.org/install/
[mxnet-official]: https://mxnet.apache.org
[official-repository]: https://github.com/zackchase/mxnet-the-straight-dope
[pipenv-github]: https://github.com/pypa/pipenv

