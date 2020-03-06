# Test Desiderata

Here are some properties making tests valuable (links lead to 5-minute videos describing each property with Kent Beck and Kelly Sutton):
- [Isolated](https://www.youtube.com/watch?v=HApI2cspQus) — tests should return the same results regardless of the order in which they are run.
- [Composable](https://www.youtube.com/watch?v=Wf3WXYaMt8E) — I should be able to test different dimensions of variability separately and combine the results.
- [Fast](https://www.youtube.com/watch?v=L0dZ7MmW6xc) — tests should run quickly.
- [Inspiring](https://www.youtube.com/watch?v=2Q1O8XBVbZQ) — passing the tests should inspire confidence
- [Writable](https://www.youtube.com/watch?v=CAttTEUE9HM) — tests should be cheap to write relative to the cost of the code being tested.
- [Readable](https://www.youtube.com/watch?v=bDaFPACTjj8) — tests should be comprehensible for reader, invoking the motivation for writing this particular test.
- [Behavioral](https://www.youtube.com/watch?v=5LOdKDqdWYU) — tests should be sensitive to changes in the behavior of the code under test. If the behavior changes, the test result should change.
- [Structure-insensitive](https://www.youtube.com/watch?v=bvRRbWbQwDU) — tests should not change their result if the structure of the code changes.
- [Automated](https://www.youtube.com/watch?v=YQlmP08dj6g) — tests should run without human intervention.
- [Specific](https://www.youtube.com/watch?v=8lTfrCtPPNE) — if a test fails, the cause of the failure should be obvious.
- [Deterministic](https://www.youtube.com/watch?v=PwWyp-wpFiw) — if nothing changes, the test result shouldn’t change.
- [Predictive](https://www.youtube.com/watch?v=7o5qxxx7SmI) — if the tests all pass, then the code under test should be suitable for production.

Some properties support each other. Automating tests makes them faster to run.

Some properties interfere with each other. Making tests more predictive of production behavior makes them slower.

Sometimes (and this is the magic), properties only seem to interfere. You can use composability to make tests faster _and_ more predictive.

The original Test Desiderata papers are [here](https://medium.com/@kentbeck_7670/test-desiderata-94150638a4b3) and [here](https://medium.com/@kentbeck_7670/programmer-test-principles-d01c064d7934).

