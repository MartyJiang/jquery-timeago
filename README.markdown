# timeago: a jQuery plugin

Timeago is a jQuery plugin that makes it easy to support automatically updating
fuzzy timestamps (e.g. "4 minutes ago" or "about 1 day ago") from ISO 8601
formatted dates and times embedded in your HTML (à la microformats).

---

## Usage(My added function)

```javascript
var fromTime = '2013-12-21';
var toTime   = new Date();
$.timeago(fromTime, toTime);
// Note: The agruments fromTime, toTime can be String, Date, number and don't need same type
```
[More detail](http://github.com/rmm5t/jquery-timeago)

[MIT License](http://www.opensource.org/licenses/mit-license.php)

