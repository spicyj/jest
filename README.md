# [Jest](http://facebook.github.io/jest/)

Painless JavaScript Unit Testing

- **Familiar Approach**: Built on top of Jasmine test framework, a familiar BDD testing environment

- **Mock by Default**: Automatically mocks CommonJS modules returned by require(), making most existing code testable

- **Short Feedback Loop**: Tests run in parallel and DOM apis are mocked so you can run tests on the command line

## Getting Started

Check out the [Getting Started](http://facebook.github.io/jest/docs/getting-started.html) tutorial. It's pretty simple!

## API

<generated_api_start />
#### The `jest` object

  - [`jest.autoMockOff()`](http://facebook.github.io/jest/docs/api.html#jest-automockoff)
  - [`jest.autoMockOn()`](http://facebook.github.io/jest/docs/api.html#jest-automockon)
  - [`jest.clearAllTimers()`](http://facebook.github.io/jest/docs/api.html#jest-clearalltimers)
  - [`jest.dontMock(module)`](http://facebook.github.io/jest/docs/api.html#jest-dontmockmodulename)
  - [`jest.genMockFromModule(moduleObj)`](http://facebook.github.io/jest/docs/api.html#jest-genmockfrommodule-moduleobj)
  - [`jest.genMockFunction()`](http://facebook.github.io/jest/docs/api.html#jest-genmockfunction)
  - [`jest.genMockFn()`](http://facebook.github.io/jest/docs/api.html#jest-genmockfn)
  - [`jest.mock(moduleName)`](http://facebook.github.io/jest/docs/api.html#jest-mockmodule-name)
  - [`jest.runAllTicks()`](http://facebook.github.io/jest/docs/api.html#jest-runallticks)
  - [`jest.runAllTimers()`](http://facebook.github.io/jest/docs/api.html#jest-runalltimers)
  - [`jest.runOnlyPendingTimers()`](http://facebook.github.io/jest/docs/api.html#jest-runonlypendingtimers)
  - [`jest.setMock(moduleName, moduleExports)`](http://facebook.github.io/jest/docs/api.html#jest-setmock-modulename-moduleexports)

#### Mock functions

  - [`mockFn.mock.calls`](http://facebook.github.io/jest/docs/api.html#mockfn-mock-calls)
  - [`mockFn.mock.instances`](http://facebook.github.io/jest/docs/api.html#mockfn-mock-instances)
  - [`mockFn.mockClear()`](http://facebook.github.io/jest/docs/api.html#mockfn-mockclear)
  - [`mockFn.mockImplementation(fn)`](http://facebook.github.io/jest/docs/api.html#mockfn-mockimplementation-fn)
  - [`mockFn.mockImpl(fn)`](http://facebook.github.io/jest/docs/api.html#mockfn-mockimpl-fn)
  - [`mockFn.mockReturnThis()`](http://facebook.github.io/jest/docs/api.html#mockfn-mockreturnthis)
  - [`mockFn.mockReturnValue(value)`](http://facebook.github.io/jest/docs/api.html#mockfn-mockreturnvalue-value)
  - [`mockFn.mockReturnValueOnce(value)`](http://facebook.github.io/jest/docs/api.html#mockfn-mockreturnvalueonce-value)

#### Config options

  - [`config.collectCoverage` [boolean]](http://facebook.github.io/jest/docs/api.html#config-collectcoverage-boolean)
  - [`config.collectCoverageOnlyFrom` [object]](http://facebook.github.io/jest/docs/api.html#config-collectcoverageonlyfrom-object)
  - [`config.modulePathIgnorePatterns` [array<string>]](http://facebook.github.io/jest/docs/api.html#config-modulepathignorepatterns-array-string)
  - [`config.rootDir` [string]](http://facebook.github.io/jest/docs/api.html#config-rootdir-string)
  - [`config.scriptPreprocessor` [string]](http://facebook.github.io/jest/docs/api.html#config-scriptpreprocessor-string)
  - [`config.setupEnvScriptFile` [string]](http://facebook.github.io/jest/docs/api.html#config-setupenvscriptfile-string)
  - [`config.setupTestFrameworkScriptFile` [string]](http://facebook.github.io/jest/docs/api.html#config-setuptestframeworkscriptfile-string)
  - [`config.testFileExtensions` [array<string>]](http://facebook.github.io/jest/docs/api.html#config-testfileextensions-array-string)
  - [`config.testPathDirs` [array<string>]](http://facebook.github.io/jest/docs/api.html#config-testpathdirs-array-string)
  - [`config.testPathIgnorePatterns` [array<string>]](http://facebook.github.io/jest/docs/api.html#config-testpathignorepatterns-array-string)
  - [`config.unmockedModulePathPatterns` [array<string>]](http://facebook.github.io/jest/docs/api.html#config-unmockedmodulepathpatterns-array-string)

#### Globally injected variables

  - [`jest`](http://facebook.github.io/jest/docs/api.html#the-jest-object)
  - `require(module)`
  - `require.requireActual(module)`
  - `describe(name, fn)`
  - `beforeEach(fn)`
  - `afterEach(fn)`
  - `it(name, fn)`
  - `it.only(name, fn)` executes [only](https://github.com/davemo/jasmine-only) this test. Useful when investigating a failure
  - `pit(name, fn)` [helper](https://www.npmjs.org/package/jasmine-pit) for promises

#### `expect(value)`

  - `.not` inverse the next comparison
  - `.toThrow(?message)`
  - `.toBe(value)` comparison using `===`
  - `.toEqual(value)` deep comparison. Use [`jasmine.any(type)`](http://jasmine.github.io/1.3/introduction.html#section-Matching_Anything_with_<code>jasmine.any</code>) to be softer
  - `.toBeFalsy()`
  - `.toBeTruthy()`
  - `.toBeNull()`
  - `.toBeUndefined()`
  - `.toBeDefined()`
  - `.toMatch(regexp)`
  - `.toContain(string)`
  - `.toBeCloseTo(number, delta)`
  - `.toBeGreaterThan(number)`
  - `.toBeLessThan(number)`
  - `.toBeCalled()`
  - `.toBeCalledWith(arg, um, ents)`
  - `.lastCalledWith(arg, um, ents)`

<generated_api_end />
