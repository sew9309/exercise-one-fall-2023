## Functions

```js

function coolFunction(arg){
    if(typeof arg==='string') return 'string';
    return 'not string'
}

const thisval = coolFunction ('hi'); //string

const coolArrowFunction = () => 'hello';

```

##Objects /* useful for storing and sorting data*/

const annoyingObject = {
{
    top: [
        {
            middle: {
                bottom: {
                    thing: 'frogs'

                }
            }
        }
    ]
}
}

annoyingObject.top[0].middle.bottom.thing //frogs

{
    "key": "value"
}