# JMeter-perfotrator
A ready-to-use JMeter project for simple performance testing with the aim to minimize manual work, the only required configurable part being the test URL list.

## Quick instructions
1. Add URLs to file [_project\urls.txt_](https://github.com/dratini/jmeter-perfotrator/blob/master/project/urls.txt), one URL per line. 
2. Start JMeter UI with _start-gui.bat_

![JMeter basic controls](http://dev.solita.fi/img/measuring-episerver-site-performance/jmeter-basic-controls.jpg)

Press START

![JMeter report view](http://dev.solita.fi/img/measuring-episerver-site-performance/jmeter-report-view.jpg)

You can also execute _start-run.bat_ to generate a result file: _results/Aggregate_Report.txt_

## Additional information
I wrote a blog post about using this tool with [Episerver sites](http://dev.solita.fi/episerver/2016/01/21/measuring-episerver-site-performance). 
The post contains further details about configuration and best-practices.