## RSVP App
This is an RSVP app. I borrowed the CSS from T3H but did JS by  myself. JS code at the bottom of HTML file.

You can preview this <a href="http://htmlpreview.github.io/?https://github.com/VladLegkowski/RSVP-App/blob/master/index.html" target="_blank">site here</a>.

## Filter by Class name in pure JS.

Clean and neat solution for hiding / displaying elements on the page with specific class.

```javascript
    function filterWhoRSVPd() {
        const li = document.querySelectorAll('li');
        li.forEach((li) => {
            const className = li.className;
            if (className === '') {
                if (li.style.display === 'none') {
                    li.style.display = 'block';
                } else {
                    li.style.display = 'none';
                }
            }
        });
    }
```

## Motivation

Learn how to code in pure JS

## License

None.
