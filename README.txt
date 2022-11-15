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
    
    2:
    use(function () {
        return [10, 20, 30 ,40];
    });

### HTML Code
    <div data-sly-use.test="test.js"></div>
    <div data-sly-list.item="${test.arr}">
        <p> Book :<b>${item.img}</b></p>
    </div>
    
    
    <div data-sly-use.test="test.js"></div>
    <div data-sly-list.item="${test}">
        <p> Book :<b>${item}</b></p>
    </div>
    
