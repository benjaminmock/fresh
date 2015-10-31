# Fresh

The original version of fresh by Andrea Franz is located at [here](https://github.com/pilu/fresh)

## New Feature

You can integrate directories that should not be watched. That could be the case, when you use some node modules. The error message that you will probably receive is the following:

    kqueue: too many open files in system

Here is the new config file with the default settings:

    root:              .
    tmp_path:          ./tmp
    build_name:        runner-build
    build_log:         runner-build-errors.log
    valid_ext:         .go, .tpl, .tmpl, .html
    excluded_dirs:     
    build_delay:       600
    colors:            1
    log_color_main:    cyan
    log_color_build:   yellow
    log_color_runner:  green
    log_color_watcher: magenta
    log_color_app:

## Author

* [Benjamin Mock](http://benjaminmock.de/)