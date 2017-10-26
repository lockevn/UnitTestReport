# UnitTestReport
UnitTestReport is a CLI program, generate HTML report from TestRunner's output


Currently support these TestRunners

 - NUnit3


### Usage: Building TestSuite-Level
point to the input file and also specify the name of the output file:

```
UnitTestReport [input-file]
UnitTestReport [input-file] [output-file]
```

where
`[input-file]` can be "C:\input\TestResult.xml"
`[output-file]` can be omitted (and it uses the input filename as output filename), or "C:\output\your-report-name.html"
