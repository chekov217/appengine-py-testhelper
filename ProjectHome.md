# Test helper python modules for GAE #

'appengine-py-testhelper' project is a collection of thin modules, that helps to write/run tests about Python on Google App Engine.

## GAETestBase ##
GAETestBase is a useful subclass of the standard unittest.TestCase. You can just write your test classes as usual by just extending GAETestBase class for utilizing this modules functionality.

With this module, you can do
  * skip to write code to setup dev environment
  * run your tests via CLI as usual
  * run your tests via GAEUnit under real production environment
  * run your tests with special overridden kind names
  * clean up entities created within your tests

See [GAETestBase](GAETestBase.md).