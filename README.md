Zumba Core
===============================

https://zumba.site


What is Zumba?
----------------
Zumba Coin (ZUMBA) is a new cryptocurrency available to the community. Our coin will take community opinions into consideration with governance deployment to MN holders.
Based on the leader of masternode cryptocurrency - Dash. 
Zumba has been enhanced and further developed. ZUMBA features the masternode technology with 80% block reward, near-instant and secure payments as well as anonymous transactions. 


Additional information, wallets, specifications & roadmap: https://zumba.site


License
-------

Zumba Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/zumbacoin/zumba/tags) are created to indicate new official,
stable release versions of Zumba Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows
and Linux, OS X, and that unit and sanity tests are automatically run.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

