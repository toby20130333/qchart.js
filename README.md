# qcharts.js

*QML bindings for Charts.js, a simple HTML5 Charts javascript library
 using the canvas element* - [chartjs.org](http://www.chartjs.org).

## Usage

To give Chart.js a try, use the ``qmlscene`` tool that comes with any
Qt5 installation.

    $ qmlscene QChartGallery.qml

To use QCharts.js into your own Qt/QML application, add this
repository as a submodule, within a ``jbQuick`` folder, inside your
toplevel qml source dir. So, assuming your project's root folder
contains a ``src`` folder for C++ code and a ``qml`` folder for QML
code, proceed as follows.

    $ cd /path/to/project/root/directory
    $ mkdir -p qml/jbQuick
    $ git submodule add git://github.com/jwintz/qchart.js.git qml/jbQuick/Charts
    $ git commit -a -m "Added QChart.js as a QML submodule."

Now, when cloning your git project, do not forget to handle submodules.

    $ git clone git://your/project/repository.git
    $ git submodule init
    $ git submodule update

Do not copy QChart.js sources in your project if you want to benefit
from updates. Updating your local submodule, use the following
command.

    $ git submodule update

## Documentation

You can find Charts.js documentation at
[chartjs.org/docs](http://www.chartjs.org/docs).

## License

QChart.js, just as Charts.js, is available under the [MIT license]
(http://opensource.org/licenses/MIT).
