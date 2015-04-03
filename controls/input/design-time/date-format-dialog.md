---
title: Date Format Dialog
page_title: Date Format Dialog | UI for ASP.NET AJAX Documentation
description: Date Format Dialog
slug: input/design-time/date-format-dialog
tags: date,format,dialog
published: True
position: 3
---

# Date Format Dialog



## 

The __Date Format Dialog__ lets you to create or edit the date format that the __RadDateInput__ control uses to display its data. There are two ways to display the Date Format Dialog:

* From the __RadDateInput__ control's [Smart Tag]({%slug input/design-time/smart-tag%}), choose the __Set Display Date Format__ link. When you choose the __Set Display Date Format__ link, the format string you create or modify is the value of the __DisplayDateFormat__ property, which controls the appearance of the date value when the control does not have focus.

* From the __RadDateInput__ control's [Smart Tag]({%slug input/design-time/smart-tag%}), choose the __Set Date Format__ link. When you choose the __Set Date Format__ link, the format string you create or modify is the value of the __DateFormat__ property, which controls the appearance of the date value when the user can edit it.![DateFormat](images/DateFormat.png)

At the top of the dialog is a table of standard ASP.NET date format strings that you can choose, along with expanded date format strings to indicate their value given the current culture settings.

* To choose a standard date-format string, select its row in the table. The expanded version of the format string automatically appears in the __Custom Date Time Format__ text box, with a preview to show the appearance of the current date and time formatted using that format string.

* To specify a format string that is not included in the standard choices, simply type the new format string in the __Custom Date Time Format__ text box. The preview updates to reflect the effects of your new format string.

# See Also

 * [Formatting Dates]({%slug input/raddateinput/formatting-dates%})