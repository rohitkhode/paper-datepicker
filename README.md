# paper-datepicker
A material design date picker component with Polymer 1.2

Why yet another polymer paper date-picker? 

I had my tryst with [this one by David Mulder](https://github.com/David-Mulder/paper-date-picker) and [this one by bendavis78](https://github.com/bendavis78/paper-date-picker)

However I encountered certain issues and decided to comeup with a solution combining best features from both above components.

[David Mulder's Date Picker](https://github.com/David-Mulder/paper-date-picker)
Not supported on Polymer 1.0.
It provides an infinite scroll. However, I wanted the year-picker to be more like Windows calendar (click on Month-Year header to see all months and then click on year header again to see all years in current decade).

[bendavis78's Date Picker](https://github.com/bendavis78/paper-date-picker)
Year selector is a scroll. No month selector. As I mentioned, I wanted more like windows calendar behavior.
No support for start-of-week and disabled-days (weekly off).
Locale support is limited to formatted date display. I needed even the dates/years to be localized.


Features
===
Supported in Polymer 1.2+,
complete locale support along with start-of-week and disabled-days.

Credits
===
 
[David Mulder](https://github.com/David-Mulder/paper-date-picker) and [bendavis78](https://github.com/bendavis78/paper-date-picker) for their respective date picker components.
