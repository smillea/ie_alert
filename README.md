# IE Alert
IE Alert is a handy jQuery plugin that shows a well designed warning message to the visitor who's trying to view your site with an older version of Internet Explorer browser, this warning message will convince your visitors to upgrade their browser to a newer version of Internet Explorer or to an another web browser.

## Example code:

- $("body").iealert({ support: "ie8" });
The warning message will appear on Internet Explorer 8,7,6

- $("body").iealert({ support: "ie7" });
The warning message will appear on Internet Explorer 7,6

- $("body").iealert({ support: "ie6" });
The warning message will appear only on Internet Explorer 6

## Change title:
- $("body").iealert({ title: "your browser is old!" });

## Change text:
- $("body").iealert({ text: "Please, update your browser" });
- $("body").iealert({ text: "Please, <font color="red">update</font> your browser" });

## Source from:
- http://nmsdvid.com/iealert/
