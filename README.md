YerScriptMediaQueries
=====================

Mediaqueries for javascript.

```javascript
var mediaqueries = new YerScriptMediaQueries();
mediaqueries.init({
    'resize_treshold': 500, // defines the time to detect if sizing has ended
    'mediaqueries': [
        {
            breakpoint: 768,
            before: function(){

                // console.log( 'fired before 768' );
            },
            after: function(){

                // console.log( 'fired after 768' );
            }
        },
        {
            breakpoint: 1024,
            before: function(){

                // console.log( 'fired before 1024' );
            },
            after: function(){

                // console.log( 'fired after 1024' );
            }
        }
    ],
});
```
