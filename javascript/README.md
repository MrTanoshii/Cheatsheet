<div align="center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="64" height="64">
</div>

## :book: Style Guide

https://developer.mozilla.org/en-US/docs/MDN/Guidelines/Code_guidelines/JavaScript

https://google.github.io/styleguide/jsguide.html

https://javascript.info/coding-style

Tools:
https://eslint.org/

## Deep Copy - String

```js
copied_string = (" " + original_string).slice(1);
```

## Console

| Method                        | Description                                                      |
| ----------------------------- | ---------------------------------------------------------------- |
| log()                         | Log                                                              |
| error()                       | Log error                                                        |
| warn()                        | Log warning                                                      |
| clear()                       | Clear the console                                                |
| time(timer_name: string)      | Start timer "timer_name"                                         |
| timeEnd(timer_name: string)   | End timer "timer_name" and log the recorded time                 |
| table({key: value})           | Log as a table to console                                        |
| count(label: string)          | Log the number of times the "label" counter has been called      |
| group(label: string)          | Group future console messages with "label"                       |
| groupEnd(label: string)       | Finish the group "label"                                         |
| groupCollapsed(label: string) | Group future console messages with "label", collapsed by default |
