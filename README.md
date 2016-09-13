<div style="display:block;text-align:center;font-size:16px">
Life circle enhancement for react-native Navigator element
<div><img src='./scene.png' style="width:100px;margin-top:20px"></img></div>
</div>

### Why
The react-native official document only offer 'didfocus' and 'willfocus' event for us to get things related scene life circle done.
with this mixin, you have the power to handle tasks with more event hooks.

```
onEnterance 	- Fired at "former to current"
onBackIn 		- Fired at "latter to current"
onWillFocus 	- Fired at "other to current",two cases above covered.
onDidFocus 		- Fired at current scene active(after animation).
onbackwardblur 	- Fired at "current will jump to latter"
onForwardBlur 	- Fired at "current will jump to former"
onWillBlur 		- Fired at "current will blur",two cases above covered.
onDidBlur 		- Fired at "current to others" animation done.Before this.componentDidUnmounte
```

🍻 Cheers!