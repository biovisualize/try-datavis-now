# Think design patterns
You can find plenty of resources to teach you how to code, but not so much to teach you how to code well. Javascript is easy to learn, at least when you start learnign it. Then you quickly find the [ugly side](https://github.com/brianleroux/wtfjs) of Javascript. Fortunately, some [good resources](http://bonsaiden.github.io/JavaScript-Garden/) can show you how to deal with it. Learning a well designed library like D3 is the opposite: it's more difficult to get started but the more you use it, the more you see the good side of Javascript. 

## Various design patterns
* Object-oriented hierarchy vs functional composition
* Procedural vs declarative

## API design
* Generic vs multi-specific
* Configuration vs convention
* Modularity
* Decoupling charts from framework
* Generic vs multi-specific
* Configuration object vs composition  
* Low level vs high level  

## Implementing the datavis pipeline

### Grammar of Graphics 

### Simple pipeline pattern

```javascript
var lineChart = piper.utils.pipeline(
    piper.data,
    piper.scaleX,
    piper.scaleY,
    piper.axisX,
    piper.axisY,
    piper.panelComponent,
    piper.lineShapes,
    piper.axisComponentX,
    piper.axisComponentY,
    piper.chartTitleComponent,
    piper.tooltipComponent
);
```

