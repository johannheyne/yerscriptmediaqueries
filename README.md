YerScriptMediaqQueries
=====================

MediaQueries for Javavascript.

```javascript
var mediaqueries = new YerScriptMediaQueries();
mediaqueries.init({
    'resize_treshold': 500, // defines the time to detect if sizing has ended
    'mediaqueries': [
        {
            breakpoint: 768,
            before: function(){

                console.log( 'before 768' );
            },
            after: function(){

                console.log( 'after 768' );
            }
        },
        {
            breakpoint: 1024,
            before: function(){

                console.log( 'before 1024' );
            },
            after: function(){

                console.log( 'after 1024' );
            }
        }
    ],
});
```
