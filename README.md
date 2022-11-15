# aem-sightly

## data-sly-list

### JS code
use(function () {
    return {
        arr: [{
            img: "bonfire.png"
        },{
            img: "meal.png"
        },
        {
            img: "img_fire.png"
        }]
    };
});

### HTML Code

<div data-sly-use.test="test.js"></div>
<div data-sly-list.item="${test.arr}">
    <p> Book :<b>${item.img}</b></p>
</div>
